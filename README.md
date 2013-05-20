# Video Annotator

Annotate online videos with text for reference

## Usage
*Most features are only implemented in youtube_test.html*<br>
Pick the relevant html file that is the web host of the video. Load the file in  modern web browser with `q=<video_id>` as a query parameter.
While playing the video, whenever you want to mark the video, click the what? button. Clicking the corresponding entry will play the video from there until the next entry, or for 3 seconds.
The preceding value pads the starting time by that many seconds. The entries are editable, so one can add any notes. The entries can be deleted by clicking the close button on the 
entry.

## Motivation
This was intended to mark parts of a video for further review.

One use case was for unsubtitled foreign language videos where instead of pausing and repeating the video to
understand a phrase, causing a break in flow, one would merely mark when one did not understand and at a suitable point, pause the video and review the marked points, repeating as
necessary. After one understood the line, one could edit the entry and add notes about it.  The problem with this was that my weak listening skills mean that I must focus very intensively on
the audio to understand, and the cognitive load of both attempting to understand the line, recognizing that I do not understand the line, and that I need to mark the video results in me being
distracted from the audio and hitting the button too late.

The other use case, which I have not had the opportunity to test, is to annotate a lecture at the points where important points are expressed or require further study.

## Todo
* Combine the handling of the various video providers into one file as they all have similar interfaces
* Try to address the problem with the foreign language case