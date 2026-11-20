# FORM! Push-Up Counter

FORM! is a camera-based push-up counter that tracks your movement and counts repetitions right in your browser. No account, downloads, or special equipment needed beyond a camera and enough space to exercise.

## How to use

1. **Set up your camera.** Place your laptop or tablet on a stable surface, side-on to your body and close to floor height. Make sure your shoulders, elbows, wrists, hips, knees, and ankles fit in the picture.
2. **Enable camera.** Allow camera access and check that the on-screen skeleton follows your movements.
3. **Set the floor line.** Adjust the **Floor position** slider until the dashed yellow line lines up with the visible floor.
4. **Start counting.** Press **Start counting**, get into a straight-arm push-up position, lower your body, and push back up. The game counts a rep after a full down-and-up movement.
5. **Check your results.** Watch the clean-rep count, knee-flagged count, movement phase, and elbow angle update as you exercise. Select **Stop** to end the session or **Reset counts** to start over.

## How counting works

- **Clean reps:** Completed push-ups with no knee-proximity warning.
- **Knee-flagged reps:** Completed push-ups where the camera detected *possible* knee contact with the floor.
- **Elbow angle:** The game estimates how far your arms bend. A repetition requires bending below roughly **100°** and returning above roughly **155°**.
- **Movement phase:** Shows where you are in the repetition (ready, up, or down).

**Important:** A knee flag is an estimate, not proof that your knee touched the floor. FORM! uses a single camera, body landmarks, and your calibrated floor line. Camera perspective or obscured joints can affect results. This is a prototype, not a validated fitness assessment.

## Game controls

- **Full Screen:** Expand the camera view. Exit with the full-screen button or your browser's exit control.
- **Show skeleton:** Toggle the pose-tracking overlay.
- **Performance:** Try **Smooth (iPad)** for lighter processing or **Standard (Mac)** for more frequent pose updates.
- **Processor:** Choose GPU or CPU before enabling the camera if tracking performance differs on your device.
- **Floor position:** Adjust the yellow reference line to match the floor.

## Troubleshooting

- **Camera won't start:** Allow camera access in your browser settings, reload the page, and use the secure `https://` GitHub Pages website.
- **Skeleton disappears or jitters:** Improve lighting, steady the device, move farther back so your whole body is visible, or try Smooth (iPad). If needed, reload and test the other processor option.
- **Push-ups aren't counting:** Use a side view with your arms clearly visible. Begin at the top with straight arms, lower until your elbows bend sufficiently, then return to full extension.
- **Knees are flagged unexpectedly:** Check the floor line and camera angle, and make sure the knees and ankles are visible. The flag is an approximation.

## Privacy

Pose estimation runs on your device in the browser. The app does not need to upload your camera video to a server or use a paid inference API. An internet connection is needed to load the website and its pose-model files.
