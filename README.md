Microblog PWA training
======================================

This project is a micro-blogging application for training purpose into transforming it into a PWA.  
It is forked from [this repo](https://github.com/octo-webf/microblog-pwa). 
 
All the steps of this course can be found as branches:  

* [Start state](https://github.com/matthieupetel/microblog-pwa/tree/master)
* [Step 1 - Install service worker](https://github.com/matthieupetel/microblog-pwa/tree/step-1-install-sw)
* [Step 2 - Manifest](https://github.com/matthieupetel/microblog-pwa/tree/step-2-manifest)
* [Step 3 - Offline appshell](https://github.com/matthieupetel/microblog-pwa/tree/step-3-offline-appshell)
* [Step 4 - Offline messages](https://github.com/matthieupetel/microblog-pwa/tree/step-4-offline-messages)
* [Step 5 - Client-side push notifications](https://github.com/matthieupetel/microblog-pwa/tree/step-5-client-side-push-notification)
* [Step 6 - Save offline post messages](https://github.com/matthieupetel/microblog-pwa/tree/step-6-save-offline-post-message)

Switch between branches to navigate through the course:
```bash
git switch -c step-1-install-sw  origin/step-1-install-sw
```

Or visit the [online app](https://microblog-pwa-0.herokuapp.com/).

Project setup
--------------------------------------

**Prerequisites:**  
You must have [node](https://nodejs.org/en/download/package-manager/) and 
[Git](https://www.atlassian.com/git/tutorials/install-git) installed on your environment.

### 1. Clone or download this repo

```bash
git clone https://github.com/matthieupetel/microblog-pwa.git
cd microblog-pwa/
```

### 2. Install dependencies

```bash
npm install
```

### 3. Launch server in background

```bash
npm start &
```

and go at `http://localhost:5000`.

Kill the node process (mac os):
```bash
ps -ef | grep node
kill -9 [PROCESS_ID]
``` 

### 4. Build application each time to apply changes

```bash
npm run build
```
