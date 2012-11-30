project101
==========

//Playing a translated text

Audio audio = Audio.getInstance();
InputStream sound  = audio.getAudio("I am a bus", Language.ENGLISH);
audio.play(sound);
