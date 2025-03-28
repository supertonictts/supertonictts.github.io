# Audio Samples Directory

This directory is for storing audio samples used in your text-to-speech research demo page.

## Recommended File Structure

Organize your audio files with a consistent naming convention:

1. **Your Method Samples**
   - `our-method-sample1.mp3` - Your TTS system output for sample text 1
   - `our-method-sample2.mp3` - Your TTS system output for sample text 2
   - etc.

2. **Baseline Method A Samples**
   - `baseline-a-sample1.mp3` - Baseline A output for sample text 1
   - `baseline-a-sample2.mp3` - Baseline A output for sample text 2
   - etc.

3. **Baseline Method B Samples**
   - `baseline-b-sample1.mp3` - Baseline B output for sample text 1
   - `baseline-b-sample2.mp3` - Baseline B output for sample text 2
   - etc.

## Audio File Guidelines

- **Format**: MP3 format is recommended for broad browser compatibility
- **Quality**: 128kbps bitrate is sufficient for speech samples
- **Duration**: Keep samples concise (10-30 seconds recommended)
- **File Size**: Try to keep files under 1MB each if possible
- **Filename**: Use descriptive but consistent filenames
- **Normalization**: Normalize audio levels across samples for fair comparison

## Demo Audio Files

The demo page will display an error message if the specified audio files are not found in this directory. Make sure to update the `src` attributes in `index.html` to match your actual filenames. 