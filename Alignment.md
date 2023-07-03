Segmenting and Aligning Speech Data
-----------------------------------

For acoustic features to be extracted and paired with the words and context of the speech, we need to be able to parse an audio waveform into words and gaps. This would require already knowing the timestamps of each word spoken, or being able to detect from a waveform where the beginning and end of a spoken word is. There may be a way to utilize transcription tools to time-correlate words, by splitting up audio files into very short intervals, and then recompiling the outputs as an array.

Information also resides in the gaps between words. Gap length, hesitations, breathing amplitude and cadence.