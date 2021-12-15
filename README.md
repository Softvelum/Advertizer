# Nimble Advertizer code samples

Here you can find examples of Nimble Advertizer usage. You can find Advertizer description here https://wmspanel.com/nimble/advertizer and full technical specification here: https://wmspanel.com/nimble/advertizer_spec 
Live demo is here: https://wmspanel.com/nimble/advertizer_demo

You can find the following examples of JSON responses from main handler:
* demo-page-ads.json is a JSON used for our demo page https://wmspanel.com/nimble/advertizer_demo
* video-tutorial-preroll.json is an used at "Add pre-roll ads to live streams easily" video tutiorial: https://www.youtube.com/watch?v=MdEoRfI6Fsk
* radio-ads.json shows pre-roll and mid-roll ads for radio stream.
* red-button.json shows how you can do the "big red button" to insert ads when it's needed immediately.
* scte35.json gives example of using ads with SCTE-35 markers - this artcile has more details https://blog.wmspanel.com/2019/06/scte53-markers-nimble-advertizer.html
* audio*.mp4 and video*.mp4 are sample ads MP4 files wich are used for ads demo at live demo mentioned above.

Some examples are specific to per-session handling:
* per-session-response.json is an example of main handler which contains session_handler section
* per-session-handler-request.json is an example of request which is sent to per-session handler by Nimble Advertizer
* per-session-handler-response.json is an example of per-session handler response to Nimble Advertizer

Read this article for more details about per-session personalized ads insertion and stats collection: https://blog.wmspanel.com/2021/05/advertizer-per-session-handler.html


Notice that some JSON files have comments, so please clean them up before using in your environment.
You can make your JSON files available via HTTP or HTTPS and point your Advertizer config there so it could take instructions to run.

Feel free to ask for more handlers and responses examples via our helpdesk: https://wmspanel.com/help
