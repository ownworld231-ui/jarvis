# Jarvis (100% free stack)

## Setup
1. Install Android Studio (free). File > Open > this folder. Let Gradle sync.
2. Run on your phone (enable USB debugging).
3. Open the app > Settings: paste a free Gemini key (aistudio.google.com), add your city.
   Optional: Home Assistant URL + token for smart home.
4. In Settings, tap "Enable notification reading" and "Enable screen control" and switch Jarvis on.
5. Tap START (first run downloads a ~40 MB offline voice model), then say "Hey Jarvis".

## Try
"Hey Jarvis, give me my briefing" | "turn off the living room light" | "read my notifications"
"what's on my screen?" | "scroll down" | "click Send" | "go back" | "open YouTube"
"set an alarm for 6:30" | "flashlight on" | "navigate to the airport" | "remember my name is Sam"
"look at this" (opens camera, then Jarvis describes the photo)

## No Android Studio? Build the APK free on GitHub
1. Make a free GitHub account, create a new repository.
2. Upload ALL files of this folder (including the hidden .github folder) to it.
3. Open the repo's Actions tab, wait for "Build Jarvis APK" to finish (about 5 min).
4. Open that run, download the "Jarvis-APK" artifact, unzip it, and install app-debug.apk on your phone.
