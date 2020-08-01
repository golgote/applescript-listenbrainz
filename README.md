# applescript-listenbrainz
An Applescript service to post Apple Music tunes I like to Listenbrainz

## what it does

This action marks the current track as _loved_ and add it to your library. Then it sends its title/artist to Listenbrainz using their API.

## how to install

You can learn how to create a Service here: https://apple.stackexchange.com/questions/100642/how-to-make-an-existing-applescript-file-to-work-as-a-service

- Open the Automator app
- Create an Action
- Set it to **No input**, **Any application**
- Add a workflow **Run applescript**
- Paste the code from the listenbrainz.applescript file there
- Change your library name     
    + in English, the library is called "Library"
    + in other languages, it gets a different name, for example in French it's called "Bibliothèque"
- Set your Listenbrainz user token directly in the code
- Save all as an Action (give it a meaningful name)

Now you should see the Action in the Services menu in any application menu.
