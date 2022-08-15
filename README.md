# alfred-zoom-personal-room

With a click, it pastes the link of your Zoom personal room, opens the room and activates your video.

![Zoom personal room](https://github.com/juanborre/alfred-zoom-personal-room/blob/main/demo.gif)

## Configuration

You need to edit the workflow in order to define your hotkey. You can do that in Alfred, going to this workflow and clicking on the very first box.

You need to configure the `{personal_id}` and the `{password}`. You can get this information inside Zoom.

If nothing happens when you activate the workflow, you may need to check the name of your Zoom app and define it in the variable `{zoom_app_name}`. You can do that in Finder under the Applications folder. By default, it is Zoom.us.

## Some notes

- You need Alfred 5
- If you use Slack, the Zoom app does not work in threads, but this shortcut does (this is quite useful actually).
- This is your personal room, not a newly created meeting. Beware of whom you are sharing the link with.