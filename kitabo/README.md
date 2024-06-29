## Claude 3.5 Sonnet

```sh
cd ~/documents/liveserver/jam/kitabo/website
pip install -r requirements.txt && jupyter-book build .
cp - r foreword/app/* _build/html/foreword/app
~/documents/liveserver/new/jbb_https.sh
ghp-import -n -p -f _build/html
```

Only need the app to be present as you `ghp-import`. The embedding will still work as a webApp in its absence