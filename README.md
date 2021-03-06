# Look4Sat: Radio satellite tracker
Ham radio and weather satellite tracker and passes predictor inspired by [Gpredict](http://gpredict.oz9aec.net/) from [Alexandru Csete, OZ9AEC](https://github.com/csete).  
Using the mavenized version of [predict4java](https://github.com/davidmoten/predict4java) lib under the hood created by [David A. B. Johnson, G4DPZ](https://github.com/g4dpz) and [Dave Moten](https://github.com/davidmoten).

The app is built using Dagger2, Retrofit2, Kotlin and Kotlin coroutines, Architecture Components and Jetpack Navigation.

<p float="left">
<img src="screenshots/scr_main_menu.jpg" width="250"/>
<img src="screenshots/scr_main_list.jpg" width="250"/>
<img src="screenshots/scr_pass_view.jpg" width="250"/>
</p>
<img src="screenshots/scr_world_map.jpg" width="750">

## Main features: 

– Calculating satellite passes for up to one week (168 hours)  
– Calculating passes for the current or manually entered location  
– Showing the list of currently active and upcoming satellite passes  
– Showing the active pass progress, polar trajectory and transceivers info  
– Showing the satellite positional data, footprint and ground track on a map  
– Offline first: pass prediction is done offline. It's up to you to decide when  
to update the TLE file and the transceivers DB. (Updates once a week are recommended)