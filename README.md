# Download Gong Videos in Bulk
This is a quick Colab notebook that allows you to bulk download all your Gong videos/audio into your Google Drive account.

You might be getting rid of your Gong subscription and need to bulk download all the videos/audio for reference later. Here's the easy button you're looking for!

Follow the Gong API instructions to obtain your API Key, API Secret Key, and API endpoint. Insert those into the appropriate places in the script.

Also place the appropriate date filters and understand that it may need to be run several times if you run into a limit of API responses (the response may be paginated, and the script could definitely be modified to automatically request the next page).

You'll need to allow Colab to access your Google Drive account for this to work.
