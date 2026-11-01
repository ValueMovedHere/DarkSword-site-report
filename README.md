```
curl -sS -D hdr_pe.txt -c cj.txt -b cj.txt -A "Mozilla/5.0 (iPhone; CPU iPhone OS 18_7 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/18.0 Mobile/15E148 Safari/604.1" -e "https://tf.dzhkfz.cn/next-chain/frame.html?c=O.E.KI" "https://tf.dzhkfz.cn/next-chain/pe_worker.js?t=1" -o pe_worker.js -w "%{http_code} %{size_download}\n"

curl -sS -D hdr_module.txt -c cj.txt -b cj.txt -A "Mozilla/5.0 (iPhone; CPU iPhone OS 18_4 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/18.0 Mobile/15E148 Safari/604.1" -e "https://tf.dzhkfz.cn/next-chain/frame.html?c=O.E.KI" "https://tf.dzhkfz.cn/next-chain/rce_module.js?t=1" -o rce_module.js -w "%{http_code} %{size_download}\n"

curl -sS -D /tmp/h.txt -c /tmp/cj.txt -b /tmp/cj.txt \
                               -A "Mozilla/5.0 (iPhone; CPU iPhone OS 18_5 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/18.0 Mobile/15E148 Safari/604.1" \
                               -e "https://tf.dzhkfz.cn/next-chain/frame.html?c=O.E.KI" \
                               "https://tf.dzhkfz.cn/next-chain/rce_loader.js?$(date +%s%3N)" | tee /tmp/rce_loader.js
```
## Phishing Site
```
https://gepvh[.]com/49646/video.html
```

## The C2
```
Domain: 
37ole7no82xtgse[.]icu
IP: 
                   UTC+8 20:26
54.254.139[.]54 -> 3.0.239[.]81
```


shebvb[.]cn

dzhkfz[.]cn

sddfgth[.]top

zxcmnbd[.]top

hsykfz[.]cn

~~wtyubz[.]top~~

wewrt[.]top

ajhsftee[.]top
