# pdf-present
A browser based tool where you can present PDF slideshows (e.g. latex / beamer slides) with a "presenter screen" which can contain notes, next/prev slide and timer.

Works by establishing a BroadcastChannel between two browser tabs or windows so you can show the other tab (show.html) to the audience and keep the control panel (index.html) in your screen. From the control panel you can change the current slide with keyboard.

# How to run
Browsers have typically disabled cross-origin access and loading of scripts, files etc. so you must use a local http server. Grab a http server of your choice e.g. "python3 -m http.server" in the folder. Copy the presentations to the same folder and navigate your browser to http://localhost:8000 and another tab or window to http://localhost:8000/show.html.
Select the presentation you want to view and press "open presentation" 



