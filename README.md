# Setting up

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FImunh0ly%2Fview-logger&env=WEBHOOK_URL&envDescription=Paste%20your%20Discord%2FGuilded%20Webhook%20URL&teamSlug=holys-projects-98ffa0cc
)

1. Make an account on [Vercel](https://vercel.com/)
2. Click on the `Deploy` button above to create the project on Vercel;
3. Create a webhook and copy its URL;
4. Put your `WEBHOOK_URL` in the `Enviroment Variables` dropdown shown during the deployment:
   ![image](https://github.com/Imunh0ly/image-host/blob/main/ex%201.png?raw=true)
5. Deploy the project (it takes around 40 seconds).

*Vercel should trigger the view-logger a few times.*


## Usage

1. Send on Discord or Guilded the link to your subdomain (it can be any page, you can choose a page to recognize the view-logger);
2. Your webhook should send something whenever someone sees the view-logger.
   * In Discord, view-loggers seems to not trigger on every platform, it does for the Android mobile app but not the browser version for example. You may also need a bit of spacing between the invisible image of the view-logger and the bottom of the conversation, by adding a reaction on your message for example.
   * In Guilded, view-loggers can only trigger once every 4 hours.
  
## Ways to hide
* method 1
   * You can hide the link by using Markdown (like `[.](https://view-logger-dun.vercel.app/)`), but the invisible image has to be loaded/visible.
* method 2
   * Paste this in front `||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||`
