<style>
.ontario-application-subheader, #ontario-header-menu-toggler  { background-color: #00682C; }
.ontario-header-button:hover { background-color: #00682C; }
</style>

<div class='documentation-only--application'>
    <div class='ontario-header__container'>
        <header class='ontario-application-header ontario-header' id='ontario-header'>
            <div class='ontario-row'>
                <div class='ontario-columns ontario-small-6 ontario-application-header__logo'>
                    <a href='https://www.ontario.ca/page/government-ontario'>
                        <img src='/assets/logos/ontario-logo--desktop.svg' alt='Ontario.ca homepage' role='img' />
                    </a>
                </div>
                <div class='ontario-columns ontario-small-6 ontario-application-header__lang-toggle'>
                    <a href='#' class='ontario-header__language-toggler ontario-header-button ontario-header-button--without-outline'>
                        Français
                    </a>
                </div>
            </div>
        </header>
        <div class='ontario-application-subheader-menu__container'>
            <section class='ontario-application-subheader'>
                <div class='ontario-row'>
                    <div class='ontario-columns ontario-small-12 ontario-application-subheader__container'>
                        <p class='ontario-application-subheader__heading'>
                            <a href='/'>Ontario Electricity Support Program</a>
                        </p>
                        <div class='ontario-application-subheader__menu-container'>
                        {% if auth %}
                            <ul class='ontario-application-subheader__menu '>
                                <li><a href='/account'>My Account</a></li>
                                <li><a href='#'>Log Out</a></li>
                            </ul>
                        {% endif %}
                            <button class='ontario-header__menu-toggler ontario-header-button ontario-header-button--with-outline' id='ontario-header-menu-toggler' aria-controls='ontario-navigation' aria-label='Show navigation menu' type='button'>
                                <svg class='ontario-icon' focusable='false' viewBox='0 0 24 24' preserveAspectRatio='xMidYMid meet'><use xlink:href='#ontario-icon-menu' id="ontario-header-menu-icon"></use></svg>
                                <span>Menu</span>
                            </button>
                        </div>
                    </div>
                </div>
            </section>
            <nav class="ontario-navigation" id="ontario-navigation">
                <button class="ontario-header__menu-toggler ontario-header-button ontario-header-button--with-outline" id="ontario-header-nav-toggler" aria-controls="ontario-navigation" aria-label="Hide navigation menu">
                    <svg class="ontario-icon" focusable="false" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"><use xlink:href="#ontario-icon-close"></use></svg>
                    <span>Menu</span>
                </button>
                <div class="ontario-navigation__container">
                    <ul>
                        <li class="ontario-show-for-small-only"><a href="/landing">Home</a></li>
                        <li class="ontario-show-for-small-only"><a href="/faqs">FAQs</a></li>
                          <li class="ontario-show-for-small-only"><a href="/forms">Program Documents</a></li>
                          <li class="ontario-show-for-small-only"><a href="/eligible">Are you eligible?</a></li>
                          <li><a href="/landing">Home</a></li>
                          <li><a href="/faqs">FAQs</a></li>
                          <li><a href="/forms">Program Documents</a></li>
                          <li><a href="/eligible">Are you eligible?</a></li>
                      </ul>
                </div>
            </nav>
        </div>
    </div>
    <div class='ontario-overlay'></div>
</div>