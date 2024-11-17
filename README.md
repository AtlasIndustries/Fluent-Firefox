# Fluent UI for Firefox 134
 
### Important Notes: 
- There are no plans for any additional development for this project. This is just a proof of concept to mimic windows 11 fluent UI on firefox. 
- Many webistes and browser elements may be broken because of this. DO NOT run it on your primary browser. 
- The CSS code is very amature. Look through it at your own discretion
- The top-right corner exit, maximize and minimize buttons are not part of this project. It is the yaru Theme by Nivuu which I forgot to change before taking the screenshots.

## Screenshots
Home Page
<img src="/Read Me Resources/HomePage.png" style="border-radius: 5px">

GitHub
<img src="/Read Me Resources/github.png" style="border-radius: 5px">

Google Drive
<img src="/Read Me Resources/googledrive.png" style="border-radius: 5px">

## Instructions
<ol>
    <li>
        Make sure you have firefox nightly 134 installed. (This Repo might be outdated. It has only been tested on this version)
    </li>
    <li>
        Go to <code>about:config</code> in the firefox URL and enable the following tags:
        <ol>
            <li>
                <code>widget.windows.mica</code>
            </li>
            <li>
                <code>browser.theme.native-theme</code>
            </li>
            <li>
                <code>browser.tabs.allow_transparent_browser</code>
            </li>
            <li>
                <code>toolkit.legacyUserProfileCustomizations.stylesheets</code>
            </li>
        </ol>
    </li>
    <li>
        Go to <code>about:preferences</code> in the firefox URL bar and click Firefox Labs from the sidebar. 
    </li>
    <li>
        Download from Releases and unzip the file or git clone the repo (you can delete the read me resources folder) Enable Sidebar and Vertical Tabs.
    </li>
    <li>
        Go to Add-ons and themes > click the gear on the top-right > choose install add-on from file > choose the .xpi file. <br>
        Note: If you want to make any changes to the theme (such as changing the accent color), install the firefox color add-on, download the firefoxColorTheme.zip file and edit the theme.
    </li>
    <li>
        Go to <code>about:profiles</code> in the URL bar and click "Open Folder" next to the Root Directory of your default profile. Go to the <code>chrome</code> folder (Create one if it doesn't exist) and copy the <code>userChrome.css</code> and <code>userContent.css</code> files into there.
    </li>
    <li>
        Install the stylus add-on from the firefox add-on store. Click import on the left side and import the necessary UserStyles from the Userstyles folder. Make sure to read the descriptions at the top of the userstyles. they may be important.
    </li>
</ol>

## Accent Color

Sorry there isn't an easy way to change the accent color universally. In the different CSS files change anything that looks orange to your prefered color. Install the firefox color add-on, download the firefoxColorTheme.zip file and edit orange there as well.