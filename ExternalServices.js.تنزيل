
const muneerClientId = '7e6f57f5-43a9-4c2b-97bc-bf2ff14b14c7';
$(document).ready(function () {
    loadMunnerCSS('https://muneer.cx/static/v1/css/muneer.min.css');
    loadMunnerScript(`https://muneer.cx/v1/js/muneer.min.js?cid=${muneerClientId}`, function () {
        initalizeMuneer();
    });
});
function loadMunnerCSS(url) {
    let link = document.createElement('link');
    link.rel = 'stylesheet';
    link.type = 'text/css';
    link.href = url;
    document.head.append(link);
}
function loadMunnerScript(url, callback) {
    let script = document.createElement('script');
    script.src = url;
    script.type = 'text/javascript';
    script.onload = callback;
    document.body.append(script);
}
function initalizeMuneer() {
    new Muneer({
        "path": "https://muneer.cx/static/v1/",
        "analyticsEndpoint": "https://stats.muneer.cx/api/v1/",
        "clientID": muneerClientId,
        "supportedLanguages": ["ar", "en"],
        "template": "aside",
        "sidebarAlign": "right",
        "popupOverlay": true,
        "popupAnimation": "fade",
        "popupScroll": true,
        "closeAnywhere": true,
        "closeButton": true,
        "popupDraggable": true,
        "popupShadow": true,
        "popupTools": true,
        "showOpenButton": true,
        "buttonTabulationIndex": 0,
        "buttonPosition": "bottom-right",
        "buttonIconPosition": "before",
        "buttonEntranceAnimation": "fade",
        "buttonHoverAnimation": "none",
        "voiceNavigationAuto": false,
        "voiceNavigationAutoHidePopup": false,
        "analytics": false,
        "accessibilityProfiles": true,
        "profileEpilepsy": true,
        "profileVisuallyImpaired": true,
        "profileCognitiveDisability": true,
        "profileMotorImpaired": true,
        "profileColorblind": true,
        "profileDyslexiaFriendly": true,
        "profileAdhdFriendly": true,
        "profileBlindUsers": true,
        "onlineDictionary": true,
        "voiceNavigation": true,
        "readableExperience": true,
        "contentScaling": true,
        "textMagnifier": true,
        "readableFont": true,
        "dyslexiaFont": true,
        "highlightTitles": true,
        "highlightLinks": true,
        "fontSizing": true,
        "lineHeight": true,
        "letterSpacing": true,
        "alignCenter": true,
        "alignLeft": true,
        "alignRight": true,
        "visuallyPleasingExperience": true,
        "darkContrast": true,
        "lightContrast": true,
        "monochrome": true,
        "highSaturation": true,
        "highContrast": true,
        "lowSaturation": true,
        "colorizing": true,
        "textColors": true,
        "titleColors": true,
        "backgroundColors": true,
        "easyOrientation": true,
        "muteSounds": true,
        "hideImages": true,
        "virtualKeyboard": true,
        "readingGuide": true,
        "usefulLinks": true,
        "stopAnimations": true,
        "readingMask": true,
        "highlightHover": true,
        "highlightFocus": true,
        "bigBlackCursor": true,
        "bigWhiteCursor": true,
        "textToSpeech": true,
        "keyboardNavigation": true,
        "accessibilityStatement": false,
        "whitelabel": true,
        "themeSwitcher": true,
        "themeDefault": "system"
    });
    var style = document.createElement('style');
    style.innerHTML = `html { --muneer-color: #10615f !important; --muneer-color-accent: #1faf6f6b !important; --muneer-color-transparent: #eaf6ef !important; --muneer-text: #414042 !important; --muneer-btn-bg: #84BC47 !important; --muneer-btn-color-hover: #84BC47 !important; } body.muneer-readable-font [class^=icon-], [class*=" icon-"] font-family: icons, sans-serif !important; }`;
    document.head.appendChild(style);
}