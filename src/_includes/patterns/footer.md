<style>
.top button {
    width: 50px;
}
.top {
    position: sticky;
    bottom: 20px;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    gap: 15px;
}
@media (max-width: 640px) {
    .top { max-width: 95%; margin: auto; }
}
@media (min-width: 641px) {
    .top { max-width: 1120px; margin: auto; }
}
</style>

<button onClick='scrollToTop()' id='actual-btt-button' class='ontario-back-to-top--default'>
    <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet">
        <use href="#ontario-icon-arrow-up"></use>
    </svg>
    Top
</button>


<footer class='ontario-footer ontario-footer--default'>
    <div class='ontario-row'>
        <div class='ontario-columns ontario-small-12'>
            <ul class='ontario-footer__links-container ontario-footer__links-container--inline'>
                <li><a class='ontario-footer__link' href='https://www.ontario.ca/page/accessibility'>Accessibility</a></li>
                <li><a class='ontario-footer__link' href='https://www.ontario.ca/page/privacy-statement'>Privacy</a></li>
                <li><a class='ontario-footer__link' href='#'>Contact us</a></li>
            </ul>
            <div class='ontario-footer__copyright'>
                <a class='ontario-footer__link' href='https://www.ontario.ca/page/copyright-information'>&copy; King's Printer for Ontario,
                    <span class='ontario-nbsp'>2012&ndash;24</span></a>
            </div>
        </div>
    </div>
</footer>