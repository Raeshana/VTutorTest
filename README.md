# VTutor SDK Setup Guide

## 1. Clone the Repository
Clone this repository from GitHub to your local machine.

## 2. Open the Project in Unity
1. Open **Unity Hub**.  
2. Click **Add > Add from Disk**.  
3. Select the `avatar_display` folder from the cloned repository.

## 3. Configure Ready Player Me Settings
Once the project is loaded in Unity:
1. Go to **Tools > Ready Player Me > Settings**.
2. Fill in the following fields:  
   - **Subdomain:** `vtutortest`  
   - **App ID:** `682bd9e589ad568f13bec829`
3. Navigate to `Assets > Avatar Loader Test`.
4. Locate the **Avatar Config** asset and drag it into the **Avatar Config** field in the **Settings** window.

<img width="500" height="800" alt="image" src="https://github.com/user-attachments/assets/e4523b00-8764-4b86-8470-417ac1fd0696" />


## 4. Locating the Frontend Files
1. Navigate to `TestAvatar/index.html`.  
2. **Animation button names** can be found under the comment:  
   `<!-- Animation buttons -->`  
3. **The URL input field** can be found under the comment:  
   `<!-- Avatar form -->`

## 5. Create an Avatar using Ready Player Me
1. Open: [https://labs.readyplayer.me/avatar/choose](https://labs.readyplayer.me/avatar/choose)  
2. Create your avatar and click **Next**.  
3. Copy the generated **avatar URL**.  
4. Paste the URL into the browser input field created in `index.html` and press **Submit**.  
5. The avatar should load successfully.  

## 6. Testing
1. Right-click `index.html`  
2. Select **Open with Live Server**

⚠️ **Note:** Rebuilding the project is not necessary when altering `index.html`.
