## Hello and welcome to the football_ai code.

0. In order to run the code install all modules in the requirements.txt

1. Run the capture_video_frames.py script to catch some frames from the video. In the current status it only captures three frames to keep the data tiny.

2. Then run the player_detection.py script to create a file which contains player coords.

3. Run draw_click_on_image.py and choose four corners witch double-click and confirm with "esc" button.

4. Now that the corners are defined you can map the original coords to the new coords in the rectangle by
running the map_player_coords_to_rectangle.py

5. In order to plot all points run the heatmap.py script. Choose first if you want to plot the original coords
or the mapped coords by specifying the path.
