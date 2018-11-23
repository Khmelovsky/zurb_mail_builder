# Email Builder

 Zurb Foundation email builder. Useless  framework for creating responsive crossplaforming emails
 
 ### Documentation
  You can  use  builder configuration from  official repository [Foundation Emails](https://github.com/zurb/foundation-emails),  but it's  have  a lot dependencies  and features which you won't using and because of that yours project will looks like a big mess.
  
  Or you can use my approach. It is easy to use and fast for configuration. Just clone  this [Repository](https://github.com/Khmelovsky/zurb_mail_builder) and follow up instructions below.
  
  ### Instalation
  In cloned repository execute this simple commands:
  
```sh
$ npm install
$ gulp
```

 ### Syntax 
 The main thing  in this tool - special syntax called **Inky**. It's has several tags and grid system clasess like in a Bootstrap. This  list of them:
  - `'<container> </container>'` 
  - `'<row> </row>'`
  - `'<columns> </columns>'`
  - `'<center> </center>'`
  -  `'<button> </button>'`
  -  `'<calloutr> </callout>'`
 
**More about syntax read there** - https://foundation.zurb.com/emails/docs/inky.html

### Start Template
Repository contain start - template and you could investigate how it works. All compiled templates placed in dist folder.

### Styles / Grid System / Variables
 You can use  use **inky** syntax with class but dint use ID, it won't work
 
 Also it has several subfolders which  very important  and **I don't recomend implement changes to files in this folders**
 
- ```Componets```
- ```Grid```
- ```Util```
**For all changes  which you want improve use** ```styles.scss``` and ```settings.scss```

**Tip:** after changes  in ```settings.scss```  you should restart gulp for changes will applied

##### That's  all, have fun!

 