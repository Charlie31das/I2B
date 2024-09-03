<text-suggester class="js-continue-container width-full z-1 signup-text-suggester" data-catalyst="">
  <div class="mx-1 mx-sm-4 my-4 px-sm-4 px-1 py-4 f4 color-shadow-small bg-gray-800-mktg rounded-2 signup-content-container">
    <h1 class="sr-only">Welcome to GitHub! Let's begin the adventure</h1>
    <div class="px-sm-0 px-4">
      <typing-effect data-lines="[&quot;Welcome to GitHub!&quot;, &quot;Let’s begin the adventure&quot;]" data-continue-to="email-container" class="js-signup-typed-welcome js-octocaptcha-hide">
        <span data-target="typing-effect.content" class="text-mono text-gray-light-mktg">Welcome to GitHub!<br>Let’s begin the adventure</span>
        <span data-target="typing-effect.cursor" class="typing-effect-cursor" hidden="">|</span>
      </typing-effect>
    </div>

    <noscript>
      <div class="my-4 text-mono color-fg-attention">
        GitHub requires JavaScript enabled to sign up for our captcha. Please enable JavaScript.
      </div>
    </noscript>

    <!-- '"` -->
    <!-- </textarea></xmp> -->
    <form class="position-relative js-octocaptcha-parent" data-turbo="false" action="/signup" accept-charset="UTF-8" method="post"><input type="hidden" data-csrf="true" name="authenticity_token" value="v2qU55BbcsLJGxJnwq9oz3SYLF/Z+dsNYv07nNlzK5r5JVD4I5qhFfEknfn3JlSq93mcWl0Z0yszOcK8nBR/5g==">
      <input type="hidden" name="return_to" id="return_to" autocomplete="off" class="form-control">
      <input type="hidden" name="invitation_token" id="invitation_token" autocomplete="off" class="form-control">
      <input type="hidden" name="repo_invitation_token" id="repo_invitation_token" autocomplete="off" class="form-control">
      <div id="email-container" class="js-continue-step-container signup-continue-step-container js-octocaptcha-hide mt-4 px-sm-0 px-4" data-step-state="active">
        <div class="mb-1">
          <label for="email" class="text-mono signup-text-prompt">
            Enter your email<sup aria-hidden="true">*</sup>
          </label>
        </div>
        <div class="d-flex flex-items-center flex-column flex-sm-row">
          <div class="d-flex flex-items-center width-full">
            <span class="signup-continue-prompt mr-2" aria-hidden="true"></span>
            <auto-check src="/email_validity_checks" class="js-prevent-default-behavior width-full mr-2" required="">
              <input id="email" class="js-continue-input js-continue-focus-target js-octocaptcha-data-field signup-input form-control input-block flex-1 border-0 pl-0 box-shadow-none color-text-white f4 text-mono" required="" autofocus="autofocus" autocomplete="off" data-target="text-suggester.input" data-octocaptcha-field-name="email_address" aria-describedby="email-err" type="email" name="user[email]" spellcheck="false">
              <input type="hidden" data-csrf="true" value="G2ml8+IIjo5W0VEj20IybJilxpTuQx5Rfb4xmpVEq4eNvhISwnmAiwcO+STGqB4fFLo1p8JrzojDxhLOr4SwIA==">
            </auto-check>
          </div>
          <button type="button" class="js-continue-button signup-continue-button form-control px-3 width-full width-sm-auto mt-4 mt-sm-0" data-continue-to="password-container" disabled="">
            Continue
          </button>
        </div>
      </div>

      <div id="password-container" class="js-continue-step-container signup-continue-step-container px-sm-0 px-4 js-octocaptcha-hide" hidden="" data-step-state="invalid">
        <div class="mt-4 mb-1">
          <label for="password" class="text-mono signup-text-prompt">
            Create a password<sup aria-hidden="true">*</sup>
          </label>
        </div>
        <div class="d-flex flex-items-center flex-column flex-sm-row">
          <div class="d-flex flex-items-center width-full">
            <span class="signup-continue-prompt mr-2" aria-hidden="true"></span>
            <visible-password class="flex-1 d-flex flex-items-center mr-3" data-catalyst="">
              <auto-check src="/password_validity_checks" class="js-prevent-default-behavior flex-1 mr-2" required="">
                <input id="password" class="form-control js-continue-input js-continue-focus-target signup-input form-control input-block flex-1 border-0 pl-0 box-shadow-none color-text-white f4 text-mono" required="" passwordrules="minlength: 15; allowed: unicode;" autocomplete="off" data-target="visible-password.input" aria-describedby="password-err" type="password" name="user[password]" spellcheck="false">
                <input type="hidden" data-csrf="true" value="3zHl58I5BrD9jYWgEh1ykTNTb+Zh4V2m0S+gDFz5Zodwf2ew0cFyKCcqOsAeNiz1Gs5gicLc7QtNmYLBrVUBDQ==">
              </auto-check>
              <button data-target="visible-password.showButton" data-action="click:visible-password#show" aria-label="Show password" type="button" data-view-component="true" class="signup-password-visibility-toggle Button--link Button--medium Button"> <span class="Button-content">
                  <span class="Button-label"><svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-eye">
                      <path d="M8 2c1.981 0 3.671.992 4.933 2.078 1.27 1.091 2.187 2.345 2.637 3.023a1.62 1.62 0 0 1 0 1.798c-.45.678-1.367 1.932-2.637 3.023C11.67 13.008 9.981 14 8 14c-1.981 0-3.671-.992-4.933-2.078C1.797 10.83.88 9.576.43 8.898a1.62 1.62 0 0 1 0-1.798c.45-.677 1.367-1.931 2.637-3.022C4.33 2.992 6.019 2 8 2ZM1.679 7.932a.12.12 0 0 0 0 .136c.411.622 1.241 1.75 2.366 2.717C5.176 11.758 6.527 12.5 8 12.5c1.473 0 2.825-.742 3.955-1.715 1.124-.967 1.954-2.096 2.366-2.717a.12.12 0 0 0 0-.136c-.412-.621-1.242-1.75-2.366-2.717C10.824 4.242 9.473 3.5 8 3.5c-1.473 0-2.825.742-3.955 1.715-1.124.967-1.954 2.096-2.366 2.717ZM8 10a2 2 0 1 1-.001-3.999A2 2 0 0 1 8 10Z"></path>
                    </svg></span>
                </span>
              </button>

              <button data-target="visible-password.hideButton" data-action="click:visible-password#hide" aria-label="Hide password" hidden="hidden" type="button" data-view-component="true" class="signup-password-visibility-toggle Button--link Button--medium Button"> <span class="Button-content">
                  <span class="Button-label"><svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-eye-closed">
                      <path d="M.143 2.31a.75.75 0 0 1 1.047-.167l14.5 10.5a.75.75 0 1 1-.88 1.214l-2.248-1.628C11.346 13.19 9.792 14 8 14c-1.981 0-3.67-.992-4.933-2.078C1.797 10.832.88 9.577.43 8.9a1.619 1.619 0 0 1 0-1.797c.353-.533.995-1.42 1.868-2.305L.31 3.357A.75.75 0 0 1 .143 2.31Zm1.536 5.622A.12.12 0 0 0 1.657 8c0 .021.006.045.022.068.412.621 1.242 1.75 2.366 2.717C5.175 11.758 6.527 12.5 8 12.5c1.195 0 2.31-.488 3.29-1.191L9.063 9.695A2 2 0 0 1 6.058 7.52L3.529 5.688a14.207 14.207 0 0 0-1.85 2.244ZM8 3.5c-.516 0-1.017.09-1.499.251a.75.75 0 1 1-.473-1.423A6.207 6.207 0 0 1 8 2c1.981 0 3.67.992 4.933 2.078 1.27 1.091 2.187 2.345 2.637 3.023a1.62 1.62 0 0 1 0 1.798c-.11.166-.248.365-.41.587a.75.75 0 1 1-1.21-.887c.148-.201.272-.382.371-.53a.119.119 0 0 0 0-.137c-.412-.621-1.242-1.75-2.366-2.717C10.825 4.242 9.473 3.5 8 3.5Z"></path>
                    </svg></span>
                </span>
              </button>
            </visible-password>
          </div>
          <button type="button" class="js-continue-button signup-continue-button form-control px-3 width-full width-sm-auto mt-4 mt-sm-0" data-continue-to="username-container" disabled="">
            Continue
          </button>
        </div>
      </div>

      <div id="username-container" class="js-continue-step-container js-octocaptcha-hide signup-continue-step-container px-sm-0 px-4" hidden="" data-step-state="invalid">
        <div class="mt-4 mb-1">
          <label for="login" class="text-mono signup-text-prompt">
            Enter a username<sup aria-hidden="true">*</sup>
          </label>
        </div>
        <div class="d-flex flex-items-center flex-column flex-sm-row">
          <div class="d-flex flex-items-center width-full">
            <span class="signup-continue-prompt mr-2" aria-hidden="true"></span>
            <auto-check src="/signup_check/username?suggest_usernames=true" http-method="GET" class="js-prevent-default-behavior width-full mr-2" required="">
              <input id="login" class="form-control js-continue-input js-continue-focus-target js-octocaptcha-data-field signup-input form-control input-block flex-1 border-0 pl-0 box-shadow-none color-text-white f4 text-mono" required="" autocomplete="off" data-octocaptcha-field-name="login" aria-describedby="login-err" type="text" name="user[login]" spellcheck="false">
            </auto-check>
          </div>
          <button type="button" class="js-continue-button signup-continue-button form-control px-3 width-full width-sm-auto mt-4 mt-sm-0" data-continue-to="opt-in-container">
            Continue
          </button>
        </div>
      </div>

      <div id="opt-in-container" class="js-continue-step-container signup-continue-step-container js-octocaptcha-hide px-sm-0 px-4" hidden="" data-step-state="complete">
        <div class="mt-4 mb-1">
          <label for="opt_in" class="text-mono signup-text-prompt">
            Email preferences
          </label>
        </div>
        <div class="d-flex flex-items-center flex-column flex-sm-row">
          <div class="d-flex flex-items-center width-full">
            <input type="checkbox" name="opt_in" id="opt_in" value="true" class="js-continue-input js-continue-focus-target signup-input form-control flex-1 signup-checkbox">
            <label class="color-fg-on-emphasis f4 text-mono text-normal position-relative pl-2" for="opt_in">
              Receive occasional product updates and announcements.
            </label>
          </div>
          <button type="button" class="js-continue-button signup-continue-button form-control px-3 width-full width-sm-auto mt-4 mt-sm-0 js-octocaptcha-load-captcha" data-continue-to="captcha-and-submit-container">
            Continue
          </button>
        </div>
      </div>

      <div id="captcha-and-submit-container" class="width-full js-continue-step-container captcha-container" data-step-state="complete" hidden="" style="position: relative; top: 0px;">
        <div class="text-mono text-bold signup-text-prompt mt-4 px-sm-0 px-4">
          Verify your account
        </div>
        <div class="js-continue-focus-target" tabindex="-1" style="outline: none;">

          <div class="my-3">

            <div class="js-octocaptcha-spinner d-flex flex-justify-center flex-items-center width-full">
              <img alt="Waiting for verification." src="https://github.githubassets.com/assets/octocat-spinner-128-9d4bc3602169.gif" width="64" height="64">
            </div>

            <div class="js-octocaptcha-success d-none d-flex flex-justify-center flex-items-center width-full">
              <svg height="64" aria-label="Account has been verified. Please continue." role="img" viewBox="0 0 24 24" version="1.1" width="64" data-view-component="true" class="octicon octicon-check color-fg-success">
                <path d="M21.03 5.72a.75.75 0 0 1 0 1.06l-11.5 11.5a.747.747 0 0 1-1.072-.012l-5.5-5.75a.75.75 0 1 1 1.084-1.036l4.97 5.195L19.97 5.72a.75.75 0 0 1 1.06 0Z"></path>
              </svg>
            </div>

            <div class="width-full" data-ga-event-category="Signup funnel entrance">
              <iframe data-src="https://octocaptcha.com?origin_page=github_signup_redesign&amp;responsive=true&amp;require_ack=true&amp;version=2" class="js-octocaptcha-frame width-full d-block v-hidden border-0 rounded-2" title="Please verify by completing this captcha."></iframe>
            </div>

            <input required="" name="octocaptcha-token" class="js-octocaptcha-token d-none" data-octocaptcha-url="https://octocaptcha.com" data-octocaptcha-timeout="30000" data-dynamically-load-captcha="true">
          </div>

        </div>

        <input class="form-control" type="text" name="required_field_2474" hidden="hidden">
        <input class="form-control" type="hidden" name="timestamp" value="1725392071027">
        <input class="form-control" type="hidden" name="timestamp_secret" value="cb44f1e4eb94da2e091959420d0ba1b7a1c2cde47e77412ce9bc0210a9efbcf6">

        <div class="px-sm-0 px-4">
          <button name="button" type="submit" class="form-control signup-submit-button width-full py-2 mt-2 js-octocaptcha-form-submit" data-disable-invalid="true" disabled="" hidden="hidden">Create account</button>
        </div>
      </div>
    </form>
  </div>
  <div class="js-continue-hint-container mx-4 px-4 f4 font-mktg text-gray-light-mktg signup-hint-container">
    <p id="email-err" data-hint-for="email" role="alert" aria-atomic="true"></p>
    <p id="password-err" data-hint-for="password" role="alert" aria-atomic="true" hidden=""></p>
    <p id="login-err" data-hint-for="login" role="alert" aria-atomic="true" hidden=""></p>
  </div>
</text-suggester>
