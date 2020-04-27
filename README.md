# **Dark**

**This repository is a collection of dark themes that I use for some messaging services, if you'd like me to add anything, let me know through an issue!
If you made a theme and would like it put here with some others, let me know by creating a PR!**

For Instagram I also have a function to make the **ENTER** key send the messages.\
\
**Yes**, I am aware that this is not working properly in **Ferdi**, as it adds an extra enter in the text box after sending.\
I believe this is due to the way **Ferdi** injects JavaScript though, as the exact same function works perfectly in **Rambox**.\
If someone has a solution, please let me know!

## **Applying the themes**

### **Rambox**

**Disclaimer**: I no longer use Rambox but I left this here for everyone who still uses it!

<details>
  <summary>Click to expand!</summary>
  
  First, find the service you wish to apply the theme to

  ![find](https://raw.githubusercontent.com/obvionaoe/dark-resources/master/images/tutorial/find.png)

  go into the settings for that service

  ![configure](https://raw.githubusercontent.com/obvionaoe/dark-resources/master/images/tutorial/configure.png)

  once you're there, click on "Advanced".

  ![advanced](https://raw.githubusercontent.com/obvionaoe/dark-resources/master/images/tutorial/advanced.png)

  A text-box will appear, copy the JavaScript code from [function.js](rambox/function.js) into it, then copy the CSS code for the service you want to theme into the `[paste css here]` area - **don't remove the backticks** - and save your changes!

  ![paste](https://raw.githubusercontent.com/obvionaoe/dark-resources/master/images/tutorial/paste.gif)

  Then press "Yes" on the service restart popup

  ![save](https://raw.githubusercontent.com/obvionaoe/dark-resources/master/images/tutorial/save.png)

  and that's it, all done and ready to use!
</details>

### **Ferdi/Franz**

<details>
  <summary>If you have Git</summary>

  Choose a folder where you want to store the themes and run the following commands:
  <details>
    <summary>Linux/MacOS</summary>

    ```bash
    $ git clone https://github.com/obvionaoe/dark.git
    $ cd dark
    $ ln -s /path/to/cloned/directory/[service]/darkmode.css ~/.config/Ferdi/recipes/[service]/darkmode.css
    ```

  Replace `[service]` by the name of the service you want to theme.\
  `/path/to/cloned/directory/` **must be an absolute path.**
  </details>
  
  <details>
    <summary>Windows</summary>

    ```bash
    $ git clone https://github.com/obvionaoe/dark.git
    $ cd dark
    $ mklink %AppData%\Franz\recipes\[service]]\darkmode.css [service]\darkmode.css
    ```
  Replace `[service]` by the name of the service you want to theme.
  </details>

  To apply the themes, just turn on dark mode inside the service settings.

</details>

<details>
  <summary>If you don't have Git</summary>
  
  Just copy the `[service]/darkmode.css` file, with `[service]` being the name of the service you want to update, into the recipe folder of that service.

  To apply the themes, just turn on dark mode inside the service settings.
  
</details>

## **Updating the themes**

### **Rambox**

Same steps you use for applying them in the first place.

### **Ferdi/Franz**

<details>
  <summary>If you have Git</summary>
  
  Just run `git pull origin master` in the repo folder you cloned and reload the services inside Ferdi, Franz or Rambox.
</details>

<details>
  <summary>If you don't have Git</summary>
  
  Just copy the `[service]/darkmode.css` file, with `[service]` being the name of the service you want to update, into the recipe folder of that service!
</details>

## **Themes**

* **Messenger** - forked from [auscompgeek/fb-messenger-dark](https://github.com/auscompgeek/fb-messenger-dark)\
(Bugfixed and improved)
&nbsp;<details>
    <summary>Screenshot</summary>
  
    ![Messenger](https://raw.githubusercontent.com/obvionaoe/dark-resources/master/images/screenshots/messenger.png)
  </details>

* **Telegram** - forked from [Web Telegram Dark & Wide Screen](https://userstyles.org/styles/155933/web-telegram-dark-wide-screen)
&nbsp;<details>
    <summary>Screenshot</summary>
  
    ![Telegram](https://raw.githubusercontent.com/obvionaoe/dark-resources/master/images/screenshots/telegram.png)
  </details>

* **WhatsApp** - forked from [vednoc/dark-whatsapp](https://github.com/vednoc/dark-whatsapp)\
(Optimized performance)
&nbsp;<details>
    <summary>Screenshot</summary>
  
    ![WhatsApp](https://raw.githubusercontent.com/obvionaoe/dark-resources/master/images/screenshots/wa.png)
  </details>