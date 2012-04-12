# Party Squirrel

This is a remix I did a while back of an Ariel Pink tune, which I decided would be a great candidate for my first open source track. It samples "Girl In A Tree" from Ariel Pink's Haunted Graffiti, a self-titled album that encompassed all of Ariel's early cassette recordings.

## Usage

This short guide assumes you have never used the Terminal before. So if you have, sorry if it's a little verbose. But it should be a clear, concise and complete guide to downloading and opening this project.

**Note: You need [Git][git] installed for all this to work...**

Open your terminal emulator (this is "Terminal" on Mac OS X, it's in **/Applications/Utilities/**).

Type the following into the prompt:

    git clone https://github.com/tubbo/party-squirrel.git "Party Squirrel"

This extracts the repository onto your computer in the folder **~/Party Squirrel/**

Go to that directory in Finder. Since you're already in Terminal, it's easiest to just type

    open "Party Squirrel"

The Finder should have popped up, opened to that directory. You should also see a `.logic` file called **Girl In A Tree.logic**. Open this file with Logic Pro 9 (just double-click it if Logic is installed) and hit the Play button to play back the current version of the track.

## Contributing

Contributions to this remix are welcome and appreciated, as long as you follow the basic ground rules:

- All instruments and effects used must be freely available, or must come packaged with Logic Pro 9.x, Reason 4.x or Ableton Live 8.x.
- Any changes made must be done on a feature branch, and pushed thusly to your own fork.
- Changes merged in must not clip anywhere, for any length of time.

### Still want to do it? Great! Here's how

***Note:*** In the following Terminal commands, any text surrounded by `<` and `>` , such as `<your-username>`, are to be replaced with the actual data that it represents.

1. [Create an account][signup] on GitHub
2. Fork the project (click the "Fork" button up at the top of the page, right under the header)
3. Download [Github For Mac][app] if you have a Mac and enter your login credentials. If you don't have a Mac, you can skip the next few steps.
4. Click your name in the sidebar and find **party-squirrel** in your list of repositories, then click **Clone to Computer** and choose a location. If you are doing this in Terminal, type: `git clone git@github.com:<your-username>/party-squirrel.git`
5. Wait for it to download (could take a while, go listen to "Stairway" again).
6. Right click the repo in "My Repositories", choose "Show In Finder", and open the project. If you are doing this in Terminal, type: `cd party-squirrel/`.
7. Click the "Branches" button on the sidebar, and then click the "+" button in your repo's only branch (master). If you are doing this in Terminal, type: `git checkout -b <your-feature-branch-name>`
8. Type the new branch name, usually it's the name of your feature like `add-bass-line`.
9. Make your changes and save the project. If you are doing this in Terminal, type: `git commit -am "<your-commit-message>"`
10. Go back to Github For Mac and you will see the files that changed. Type out a short summary of what happened, then a longer description if you need it. Click the button with the arrows and "+" on it next to "Commit" to both commit and publish this branch to Github. If you are doing this in Terminal, type: `git push origin master`

Once you've pushed to Github, visit your fork in your web browser and click "Pull Request" at the top of the screen. Give a thorough description and nice title for your feature, and I'll get notified to merge it in.

## License

This project was released under an open-source license. What that essentially means is you can download and remix this track for commercial release, but publishing rights are still owned by the author of the original work.

Copyright 2012 [Tom Scott][tubbo]

   Licensed under the Open Music License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       https://github.com/tubbo/party-squirrel/wiki/License

   Unless required by applicable law or agreed to in writing, music 
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

[git]: http://git-scm.com
[app]: http://mac.github.com/
[signup]: https://github.com/signup/free
[license]: https://github.com/tubbo/party-squirrel/wiki/License
[tubbo]:https://github.com/tubbo
