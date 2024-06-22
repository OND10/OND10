```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>OND</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width" />
    <link rel="stylesheet" href="styles.css" />
    

  </head>
  <body>
  <div class="card" data-state="#about">
  <div class="card-header">
    <div class="card-cover" style="background-image: url('https://images.unsplash.com/photo-1549068106-b024baf5062d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=934&q=80')"></div>
    <img class="card-avatar" src="./myphoto.jpg" alt="avatar" />
    <h1 class="card-fullname">Osama Dammag</h1>
    <h2 class="card-jobtitle">Computer Science</h2>
  </div>
  <div class="card-main">
    <div class="card-section is-active" id="about">
      <div class="card-content">
        <div class="card-subtitle">ABOUT</div>
        <p class="card-desc">My name is Osama, also known online as OND. I'm a 22-year-old backend developer from Sana'a, Yemen.
        </p>
      </div>
      <div class="card-social">
        <a href="https://t.me/@OND10" target="_blank">
            <svg  viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M14.5 1.5L0.5 6.5L4.5 8.5L10.5 4.5L6.5 9.5L12.5 13.5L14.5 1.5Z"  stroke-linejoin="round"/>
                </svg>
        </a>
        <a href="https://github.com/OND10" aria-label="Homepage" class="footer-octicon" title="GitHub" target="_blank">
            <svg aria-hidden="true" class="octicon octicon-mark-github" height="24" version="1.1" viewBox="0 0 16 16" width="24"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path>
            </svg>
        </a>
        <a href="https://www.instagram.com/osamadammaj?igsh=MTkybGM0MDlsMGoycg==" target="_blank">
            <svg viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
                <path d="M301 256c0 24.852-20.148 45-45 45s-45-20.148-45-45 20.148-45 45-45 45 20.148 45 45zm0 0" />
                <path d="M332 120H180c-33.086 0-60 26.914-60 60v152c0 33.086 26.914 60 60 60h152c33.086 0 60-26.914 60-60V180c0-33.086-26.914-60-60-60zm-76 211c-41.355 0-75-33.645-75-75s33.645-75 75-75 75 33.645 75 75-33.645 75-75 75zm86-146c-8.285 0-15-6.715-15-15s6.715-15 15-15 15 6.715 15 15-6.715 15-15 15zm0 0" />
                <path d="M377 0H135C60.562 0 0 60.563 0 135v242c0 74.438 60.563 135 135 135h242c74.438 0 135-60.563 135-135V135C512 60.562 451.437 0 377 0zm45 332c0 49.625-40.375 90-90 90H180c-49.625 0-90-40.375-90-90V180c0-49.625 40.375-90 90-90h152c49.625 0 90 40.375 90 90zm0 0" />
            </svg>
        </a>
        <a href="https://www.linkedin.com/in/osama-dammag-%F0%9F%87%B5%F0%9F%87%B8-b40739221?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">
            <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path d="M23.994 24v-.001H24v-8.802c0-4.306-.927-7.623-5.961-7.623-2.42 0-4.044 1.328-4.707 2.587h-.07V7.976H8.489v16.023h4.97v-7.934c0-2.089.396-4.109 2.983-4.109 2.549 0 2.587 2.384 2.587 4.243V24zM.396 7.977h4.976V24H.396zM2.882 0C1.291 0 0 1.291 0 2.882s1.291 2.909 2.882 2.909 2.882-1.318 2.882-2.909A2.884 2.884 0 002.882 0z" />
            </svg>
        </a>
      </div>
    </div>
    <div class="card-section" id="experience">
      <div class="card-content">
        <div class="card-subtitle">PROJECTS</div>
        <div class="card-timeline">
          <div class="card-item" data-year="2020">
            <div class="card-item-title">Front-end Developer at <span>JotForm</span></div>
            <div class="card-item-desc">Disrupt stumptown retro everyday carry unicorn.</div>
          </div>
          <div class="card-item" data-year="2016">
            <div class="card-item-title">UI Developer at <span>GitHub</span></div>
            <div class="card-item-desc">Developed new conversion funnels and disrupt.</div>
          </div>
          <div class="card-item" data-year="2018">
            <div class="card-item-title">Illustrator at <span>Google</span></div>
            <div class="card-item-desc">Onboarding illustrations for App.</div>
          </div>
          <div class="card-item" data-year="2020">
            <div class="card-item-title">Full-Stack Developer at <span>CodePen</span></div>
            <div class="card-item-desc">Responsible for the encomposing brand expreience.</div>
          </div>
        </div>
      </div>
    </div>
    <div class="card-section" id="contact">
      <div class="card-content">
        <div class="card-subtitle">CONTACT</div>
        <div class="card-contact-wrapper">
          <div class="card-contact">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z" />
              <circle cx="12" cy="10" r="3" /></svg>
            Algonquin Rd, Three Oaks Vintage, MI, 49128
          </div>
          <div class="card-contact">
            <svg xmlns="http://www.w3.org/2000/svg" viewbox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07 19.5 19.5 0 01-6-6 19.79 19.79 0 01-3.07-8.67A2 2 0 014.11 2h3a2 2 0 012 1.72 12.84 12.84 0 00.7 2.81 2 2 0 01-.45 2.11L8.09 9.91a16 16 0 006 6l1.27-1.27a2 2 0 012.11-.45 12.84 12.84 0 002.81.7A2 2 0 0122 16.92z" /></svg>(269) 756-9809</div>
          <div class="card-contact">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z" />
              <path d="M22 6l-10 7L2 6" /></svg>
            william@rocheald.com
          </div>
          <button class="contact-me">WORK TOGETHER</button>
        </div>
      </div>
    </div>
    <div class="card-buttons">
      <button data-section="#about" class="is-active">ABOUT</button>
      <button data-section="#experience">PROJECTS</button>
      <button data-section="#contact">CONTACT</button>
    </div>
  </div>
</div>
    <script src="script.js"></script>
  </body>
</html>
```
