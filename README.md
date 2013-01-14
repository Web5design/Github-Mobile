Github Mobile
=============

Watch this repo to get alerts about this project.


<img src="https://github.com/jakiestfu/Github-Mobile/raw/master/screens/vanity/vanity.jpeg">

* <b><u>View the retinas for the <a href="https://github.com/jakiestfu/Github-Mobile/raw/master/screens/real/login_v1.png">Login Screen</a> and the <a href="https://github.com/jakiestfu/Github-Mobile/raw/master/screens/real/news_v1.png">News Feed</a></u></b>
* <b><u>View the retinas for the <a href="https://github.com/jakiestfu/Github-Mobile/raw/master/screens/real/profiles_v1.png">Profiles V1</a> and the <a href="https://github.com/jakiestfu/Github-Mobile/raw/master/screens/real/modals_v1.png">Modal Dialogs</a></u></b>
* <b><u>View the retinas for the <a href="https://github.com/jakiestfu/Github-Mobile/raw/master/screens/real/profiles_v2.png">Profiles V2</a>, <a href="https://github.com/jakiestfu/Github-Mobile/raw/master/screens/real/activity_list.png">Activities</a>, <a href="https://github.com/jakiestfu/Github-Mobile/raw/master/screens/real/starred_list.png">Starred Repos</a>, and <a href="https://github.com/jakiestfu/Github-Mobile/raw/master/screens/real/repo_list.png">Repos list</a></u></b>


## What should I know?
* I've only worked on it a single day, obviously it's not released yet, just want to clarify right away
* Uses GitHub's <a href="http://developer.github.com/v3/" target="_blank">V3 API</a>
* Stores Access Token from OAuth with Local Storage, giving this webapp ***persistance***
* Read + Write (at least what *can* be written while mobile, stars, followers, issues, etc) 

## What are you going to do?

* The entire GitHub Dashboard
* Users + relations, and ability to follow/unfollow
* Repos, ability to star, fork, submit issues
* Issues, Create, Discuss, Close
* Modify Account
* Notifications (no intent for native alerts at the moment)
* Search Search Search

When all is said and done, instead of uploading this to Apples App store, I will release it on... Bitbucket! 

Just kidding, It will be open sourced on GitHub under the MIT license. The current GitHub clients in the App Store all look like crap and *are not free*. What the fuck?

## Resource List
* Modified version of <a href="https://github.com/gilbitron/PIP" target="_blank">PIP</a> from @gilbitron, thanks!
* <a href="https://github.com/maker/ratchet" target="_blank">Ratchet</a>
* <a href="http://sparkyjs.com/" target="_blank">Unreleased, V2 of Sparky.js which is jQuery <b>independent</b> (will release soon)</a>
* <a href="https://github.com/KnpLabs/php-github-api" target="_blank">PHP API Library</a> from KnpLabs
* <a href="https://github.com/kriswallsmith/Buzz" target="_blank">Buzz</a>
* <a href="http://www.fontspace.com/k-type/collegiate">Collegiate</a> (not the *actual* font [anymore])
* <a href="http://icomoon.io/app/">IcoMoon</a> icon generator. Navigate to IcoMoon, and in the lower left hand corner, click "Load" and use the json file from <a href="https://gist.github.com/raw/4491033/70697995ec79491656a5c94ab71dffb4f03196ae/IcoMoon%20Session.json" target="_blank">this gist</a> to view the set. (Thanks again, @ColeTownsend)

And for the screens:

* <a href="http://www.pixeden.com/psd-mock-up-templates/3/4-view-iphone-5-psd-vector-mockup" target="_blank">3/4 View iPhone 5</a>


## Changelog: What has been done?
### 1-12-2013
* Local Storage caching, blazing fast
* "Shake to Clear Cache" feature
* Began single repo screen
* Tightened some UI

### 1-11-2013
* Created Starred List
* Created User Activities List
* Created Repository List
* Tweaked Profile design
* Star/Unstar functionality
* Updates to Push.js, might be the only js used from Ratchet

### 1-10-2013
* Tightened up authentification on later calls to the GitHub API
* Created Profiles
* Profiles include the shiny new Contributions Graph that can be scrolled horizantally
* Follow/Unfollow Functionality
* Modal Implementation

### 1-9-2013
* Initial Issues list
* Starred Repos List
* Created Sexy GitHub-like Modals
* Started User Profiles
* Updated Event bindings

### 1-8-2013
* Consolidation, organization, gettin this mofo off the ground
* Login Screen synchronizes access token between local storage and session storage for ease of access
* Complete OAuth flow within a webapp (never navigates to Mobile Safari)
* First poll of actual News Feed (If anyone could answer my question at the very bottom, I'd appreciate it!)
