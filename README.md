# code_AI_programming

Indien je zelf de software wilt uitproberen kun je de code repo clonen met “git clone”. Daarna voer volgend commando uit in het project:

```bash
pip install -r requirements.txt
```

Hiermee kun je enkel de detector gebruiken, dit kan door volgend commando uit te voeren:

```bash
python .\detect_mask_video.py
```

Indien je ook de trainer wilt uitvoeren, moet je volgende commando’s uitvoeren:

```bash
pip install pillow
pip install --upgrade tensorflow
conda install -c conda-forge scikit-learn
```

Om de trainer uit te voeren:

```bash
python .\train_mask_detector.py
```
