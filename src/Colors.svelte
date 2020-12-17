<style>

  :global(:root) {

    --lightest-gray: #dee2e6;
    --lighter-gray: #ced4da;
    --light-gray: #adb5bd;
    --gray: #868e96;
    --dark-gray: #495057;
    --darker-gray: #343a40;
    --darkest-gray: #212529;
    --lightest-purple: #e5dbff;
    --lighter-purple: #d0bfff;
    --light-purple: #b197fc;
    --purple: #9775fa;
    --dark-purple: #845ef7;
    --darker-purple: #7048e8;
    --darkest-purple: #5f3dc4;
    --lightest-blue: #dbe4ff;
    --lighter-blue: #bac8ff;
    --light-blue: #91a7ff;
    --blue: #5c7cfa;
    --dark-blue: #4c6ef5;
    --darker-blue: #3b5bdb;
    --darkest-blue: #364fc7;
    --lightest-green: #c3fae8;
    --lighter-green: #63e6be;
    --light-green: #20c997;
    --green: #12b886;
    --dark-green: #0ca678;
    --darker-green: #099268;
    --darkest-green: #087f5b;
    --lightest-yellow: #fff3bf;
    --lighter-yellow: #ffec99;
    --light-yellow: #ffe066;
    --yellow: #ffd43b;
    --dark-yellow: #fcc419;
    --darker-yellow: #fab005;
    --darkest-yellow: #f59f00;
    --lightest-orange: #ffe8cc;
    --lighter-orange: #ffc078;
    --light-orange: #ffa94d;
    --orange: #fd7e14;
    --dark-orange: #f76707;
    --darker-orange: #e8590c;
    --darkest-orange: #d9480f;
    --lightest-red: #ffe3e3;
    --lighter-red: #ffa8a8;
    --light-red: #ff8787;
    --red: #fa5252;
    --dark-red: #f03e3e;
    --darker-red: #e03131;
    --darkest-red: #c92a2a;
    --black: var(--darkest-gray);
    --white: #ffffff;

    /* light and dark mode */
    --background-light: var(--white);
    --background-dark: var(--black);
    --foreground-light: var(--black);
    --foreground-dark: var(--white);


    /* these build on existing colors */

    --input-border: var(--light-gray);
    --menu-border: var(--light-gray);
    --box-shadow: var(--light-gray);


    --tooltip-bg: var(--black);
    --tooltip-bg-opacity: 1;
    --tooltip-fg: var(--white);

    --overlay: var(--black);
    --overlay-opacity: 0.25;


    /* z-index */

    --z-index-overlay: 9;
    --z-index-menu: 10;
    --z-index-tooltip: 90;
    --z-index-modal: 1000;

    /* state colors */
    --critical: var(--dark-red);
    --critical-hover: var(--red);
    --critical-active: var(--darkest-red);
    --critical-disabled: var(--light-red);

    --warning: var(--dark-yellow);
    --warning-hover: var(--yellow);
    --warning-active: var(--darkest-yellow);
    --warning-disabled: var(--light-yellow);

    --ok: var(--dark-green);
    --ok-hover: var(--green);
    --ok-active: var(--darkest-green);
    --ok-disabled: var(--light-green);

    --primary: var(--blue);
    --primary-hover: var(--dark-blue);
    --primary-active: var(--darkest-blue);
    --primary-disabled: var(--light-blue);

    --neutral: var(--gray);
    --neutral-hover: var(--dark-gray);
    --neutral-active: var(--darkest-gray);
    --neutral-disabled: var(--light-gray);


    --code: var(--primary);


    --padding-input-embedded-icon: 40px;

    --icon-size: 24px;

    /* icon colors */

    --icon-color-normal: var(--black);
    --icon-color-normal-hover: var(--blue);
    --icon-color-normal-active: var(--darker-blue);
    --icon-color-normal-disabled: var(--gray);

    --icon-color-primary: var(--blue);
    --icon-color-primary-hover: var(--light-blue);
    --icon-color-primary-active: var(--darker-blue);
    --icon-color-primary-disabled: var(--lighter-blue);

    --icon-color-critical: var(--red);
    --icon-color-critical-hover: var(--light-red);
    --icon-color-critical-active: var(--darker-red);
    --icon-color-critical-disabled: var(--lighter-red);




    --menu-background: var(--white);
    --menu-hover: var(--white);
    --menu-active: var(--white);
    --menu-disabled: var(--white);

    --list-row-highlight: #f1f1f1;

  }

</style>
