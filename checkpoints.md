# Checkpoints

Click on the link and click download to download the file

- Step 1 (Create item)
    - [intents](./code/intents/intents.step.1.zip)
    - [fulfillment](./code/functions/index.step.1.js)
- Step 2 (Show list)
    - [intents](./code/intents/intents.step.2.zip)
    - [fulfillment](./code/functions/index.step.2.js)
- Step 3 (Complete item)
    - [intents](./code/intents/intents.step.3.zip)
    - [fulfillment](./code/functions/index.step.3.js)
- Step 4 (Update item)
    - [intents](./code/intents/intents.step.4.zip)
    - [fulfillment](./code/functions/index.step.4.js)

## Importing or restoring intents

Follow these instructions to configure your Dialogflow to the state after a step.

- Download the ZIP file you want from above
- Open up the Dialogflow console
- Click on the gear icon next to your project name to open up the settings
- Click on the "Export and Import" tab
- If you only want to overwrite the intents written up to that step, click on "Import from ZIP"
- If you want to overwrite all intents, click on "Restore from ZIP"
- Select the ZIP file you just downloaded
- Type "IMPORT" or "RESTORE" and click the Import button
- Click "Done"

## Importing fulfillment

- Copy and paste the appropriate code from above into your inline editor on Dialogflow
- Paste in your config from Firebase
- Click "Deploy"
