# Distru Email Templates

Emails Templates for HTML emails used in Distru is all located here.

## Build Commands

Run `npm start` to kick off the build process. A new browser tab will open with a server pointing to your project files.

Run `npm run build` to inline your CSS into your HTML along with the rest of the build process.

Run `npm run zip` to build as above, then zip HTML and images for easy deployment to email marketing services. 

## Speeding Up Your Build

If you create a lot of emails, your build can start to slow down, as each build rebuilds all of the emails in the
repository. A simple way to keep it fast is to archive emails you no longer need by moving the pages into `src/pages/archive`.
You can also move images that are no longer needed into `src/assets/img/archive`. The build will ignore pages and images that
are inside the archive folder.

## Formatting Output Emails

To copy an email over to Distru, go into the `./dist` folder after running `npm run build` and find the properly compiled version of the email
you want to use.  The email will be minified, so visit [freeformatter](https://www.freeformatter.com/html-formatter.html) in order to properly format
the HTML prior to pasting into Distru.

## Testing Emails

Use [inboxinspector](http://www.inboxinspector.com/) to test how your HTML email looks on archaic windows clients

