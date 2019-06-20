The Media Options tab is used to set various media specific options depending on the media type selected. For a description of each media option by media type, please see the links below (the Media Manager may not include all options listed)

- **[Flash](http://kb2.adobe.com/cps/127/tn_12701.html#main_Optional_attributes_and_possible_values "Flash Options")[](http://kb2.adobe.com/cps/127/tn_12701.html#main_Optional_attributes_and_possible_values "Flash Options")**
- [**Quicktime**](http://support.apple.com/kb/TA26486?viewlocale=en_US "Quicktime Options")
- [**Windows Media**](http://www.w3schools.com/media/media_playerref.asp "Windows Media Options")
- **[DivX](http://labs.divx.com/node/16584 "DivX Options")**
- [**Silverlight**](http://msdn.microsoft.com/en-us/library/cc838259(v=vs.95).aspx "Silverlight Options")
- [**HTML5 Video**](#html5video "HTML5 Video")
- [**HTML5 Audio**](#html5audio "HTML5 Audio")

### <a name="html5video">HTML5 Video</a>

Descriptions of these options is taken from the Mozilla Developer Wiki - <https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video> - and is used under the terms of the [Creative Commons Attribution-ShareAlike license](http://creativecommons.org/licenses/by-sa/2.5/ "http://creativecommons.org/licenses/by-sa/2.5/")

**Autoplay**

A Boolean attribute; if specified, the video will automatically begin to play back as soon as it can do so without stopping to finish loading the data.

**Controls**

If this attribute is present, the browser will offer controls to allow the user to control video playback, including volume, seeking, and pause/resume playback.

**Loop**

A Boolean attribute; if specified, we will, upon reaching the end of the video, automatically seek back to the start.

**Mute**

A Boolean attribute which indicates the default setting of the audio contained in the video. If set, the audio will be initially silenced. Its default value is false, meaning that the audio will be played when the video is played.

**Preload**

This enumerated attribute is intended to provide a hint to the browser about what the author thinks will lead to the best user experience. It may have one of the following values:

- none: hints that either the author thinks that the user won't need to consult that video or that the server wants to minimize its traffic; in others terms this hint indicates that the video should not be cached.
- metadata: hints that though the author thinks that the user won't need to consult that video, fetching the metadata (e.g. length) is reasonable.
- auto: hints that the user needs have priority; in others terms this hint indicated that, if needed, the whole video could be downloaded, even if the user is not expected to use it.
- the empty string: which is a synonym of the auto value.

If not set, its default value is browser-defined (i.e. each browser can choose its own default value), though the spec advises it to be set to metadata.

**Poster**

A URL indicating a poster frame to show until the user plays or seeks. If this attribute isn't specified, nothing is displayed until the first frame is available; then the first frame is displayed as the poster frame.

The poster image can be selected by clicking on the File Browser icon on the right of the text box.

**Source**

A URL to an alternate format of the video file, eg: ogg, webm etc.

The set a source URL, click in the text box, then select the file from the File Browser list.

**Fallback**

A URL to an mp4 or flv video file to be used for playback on browsers that do not support the <video> tag.

 <span style="line-height: 16.2000007629395px;">The set a fallback URL, click in the text box, then select the file from the File Browser list.</span>

### <a name="html5audio">HTML5 Audio</a>

Descriptions of these options is taken from the Mozilla Developer Wiki - <https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio> - and is used under the terms of the [Creative Commons Attribution-ShareAlike license](http://creativecommons.org/licenses/by-sa/2.5/ "http://creativecommons.org/licenses/by-sa/2.5/")

**Autoplay**

A Boolean attribute; if specified (even if the value is "false"!), the audio will automatically begin to play back as soon as it can do so without stopping to finish loading the data.

**Controls**

If this attribute is present, the browser will offer controls to allow the user to control audio playback, including volume, seeking, and pause/resume playback.

**Loop**

A Boolean attribute, when specified, will automatically seek back to the start upon reaching the end of the audio.

**Preload**

This enumerated attribute is intended to provide a hint to the browser about what the author thinks will lead to the best user experience. It may have one of the following values:

- none: hints that either the author thinks that the user won't need to consult that audio or that the server wants to minimize its traffic; in others terms this hint indicates that the audio should not be cached;
- metadata: hints that though the author thinks that the user won't need to consult that audio, fetching the metadata (e.g. length) is reasonable;
- auto: hints that the user needs have priority; in others terms this hint indicated that, if needed, the whole audio could be downloaded, even if the user is not expected to use it;
- the empty string: which is a synonym of the auto value.

If not set, its default value is browser-defined (i.e. each browser can choose its own default value), though the spec advises it to be set to metadata.

**Source**

A URL to an alternate format of the audio file, eg: ogg, webm etc.

<span style="line-height: 16.2000007629395px;">The set a source URL, click in the text box, then select the file from the File Browser list.</span>

**Fallback**

A URL to an mp3 audio file to be used for playback on browsers that do not support the <audio> tag.

<span style="line-height: 16.2000007629395px;">The set a fallback URL, click in the text box, then select the file from the File Browser list.</span>