# IMEMNet-C
Designed for multimodal research involving images, music, and musical captions, IMEMNet-C is an extended version of the [IMEMNet](https://github.com/linkAmy/IMEMNet/) dataset. This dataset bridges the gap between modalities by providing additional textual descriptions (musical captions) for music data, enabling deeper exploration of multimodal relationships. This dataset is from Artificial Intelligence for Music workshop at AAAI 2025.

## Key Features
- Multimodal data:
    - Images: 24,756 real-world images.
    - Music Clips: 25,944 music clips
    - Musical Captions: Text descriptions corresponding to the music clips.
- Emotion-Annotated
    - Valence and Arousal (VA) annotations normalized to a [0, 1] range.
    - Enables emotional alignment across modalities.

## Source Datasets
IMEMNet-C is composed of four datasets: 
[DEAM](https://cvml.unige.ch/databases/DEAM/), [IAPS](https://www.imageemotion.org/), and [EMOTIC](https://s3.sunai.uoc.edu/emotic/index.html). To use IMEMNet-C, you must obtain permission and download these datasets.

## Data Format
### Image VA CSV
Image IDs: Correspond to image filenames with extensions .jpg or .JPG.
row ID | Image ID | Valence  | Arousal  |
| --------| -------- | -------- | -------- |
0 | 3053     | 0        | 0.921847 |
1 | 3102     | 0.012802 | 0.863233 |

### Music VA CSV
Clip IDs: Correspond to audio filenames with extensions .wav or .WAV.
row ID| Clip ID  | Valence  | Arousal  | Caption                                                                            |
| -| ------- | -------- | -------- | ---------------------------------------------------------------------------------- |
0  | 725-16   | 0.671875 | 0.566878 | The jazz song showcases a vibraphone solo melody. It is accompanied by punchy snare and kick hits, shimmering cymbals, and a groovy bass guitar. The composition conveys an energetic and passionate mood.     |
1 | 118-12   | 0.539571 | 0.416638 | The instrumental piece showcases a medium tempo with a keyboard accompaniment. It has a steady drumming rhythm and a percussive bass line. Various percussion hits are incorporated for added texture. The composition is energetic and passionate. Despite the low audio quality, the musical elements remain distinct. |

