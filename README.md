# Background video Player

# This application will demonstrate how can we play video when Application is not in foreground

# Problem: 
For playing video we use videoView which works as per the activity life cycle and as a result once we close the activity or activity goes into onPuase() state the video view gets invalidated and as a result video gets stopped.
