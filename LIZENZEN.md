# Herkunft und Lizenzen der Modelle

Jedes Modell gehört seinem Herausgeber und steht unter dessen Lizenz. Die Dateien sind unverändert; die Originalquelle je Datei steht in `PRUEFSUMMEN.txt`.

| Datei | Modell | Herausgeber / Quelle | Lizenz |
|---|---|---|---|
| `model.bin` (geteilt), `config.json`, `preprocessor_config.json`, `tokenizer.json`, `vocabulary.json` | Whisper large-v3-turbo, CTranslate2-Fassung (int8) | OpenAI (Whisper); Umwandlung: Zoont, huggingface.co/Zoont/faster-whisper-large-v3-turbo-int8-ct2 | MIT (Whisper) |
| `stimme.onnx` | WeSpeaker ResNet34-LM, trainiert auf VoxCeleb | WeSpeaker, huggingface.co/Wespeaker/wespeaker-voxceleb-resnet34-LM | CC BY 4.0 (folgt der Lizenz des VoxCeleb-Datensatzes) |
| `yunet.onnx` | YuNet Gesichtserkennung (2023mar) | OpenCV Zoo, github.com/opencv/opencv_zoo | MIT |
| `rnnoise/cb.rnnn` | RNNoise-Modell „conjoined-burgers“ | Gregor Richards, github.com/GregorR/rnnoise-models | keine benannte Lizenz; laut README des Herausgebers nicht urheberrechtlich geschützt |
| `rvm/rvm_mobilenetv3_fp32.onnx` | Robust Video Matting (MobileNetV3) | Peter Lin u. a., github.com/PeterL1n/RobustVideoMatting | GPL-3.0, Lizenztext: https://www.gnu.org/licenses/gpl-3.0.txt |

Namensnennung nach CC BY 4.0: „WeSpeaker ResNet34-LM“ von WeSpeaker, trainiert auf VoxCeleb (Nagrani, Chung, Zisserman).

Hinweis eines Herausgebers auf einen Fehler in dieser Liste: bitte als Issue in diesem Repo melden.
