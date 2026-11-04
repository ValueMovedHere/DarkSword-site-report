```
curl -sS -D hdr_pe.txt -c cj.txt -b cj.txt -A "Mozilla/5.0 (iPhone; CPU iPhone OS 18_7 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/18.0 Mobile/15E148 Safari/604.1" -e "https://tf.dzhkfz.cn/next-chain/frame.html?c=O.E.KI" "https://tf.dzhkfz.cn/next-chain/pe_worker.js?t=1" -o pe_worker.js -w "%{http_code} %{size_download}\n"

curl -sS -D hdr_module.txt -c cj.txt -b cj.txt -A "Mozilla/5.0 (iPhone; CPU iPhone OS 18_4 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/18.0 Mobile/15E148 Safari/604.1" -e "https://tf.dzhkfz.cn/next-chain/frame.html?c=O.E.KI" "https://tf.dzhkfz.cn/next-chain/rce_module.js?t=1" -o rce_module.js -w "%{http_code} %{size_download}\n"

curl -sS -D /tmp/h.txt -c /tmp/cj.txt -b /tmp/cj.txt \
                               -A "Mozilla/5.0 (iPhone; CPU iPhone OS 18_5 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/18.0 Mobile/15E148 Safari/604.1" \
                               -e "https://tf.dzhkfz.cn/next-chain/frame.html?c=O.E.KI" \
                               "https://tf.dzhkfz.cn/next-chain/rce_loader.js?$(date +%s%3N)" | tee /tmp/rce_loader.js
```
## Phishing Sites
```
https://gepvh[.]com/49646/video.html--\
https://qyul30[.]com------------------- => https://tf[.]dzhkfz[.]cn/channel/O.E.KI/weifile/weifile[.]html
https://99jj16[.]com------------------/

dkj84dkfgljf74[.]vip \
                       https://www[.]jx9adrpc5z8094di7[.]net/channel/J.I.N2/weifile/weifile[.]html => 待归因
https://baoz3[.]top  /
                                 /\
                                 || 类似
                                 \/
      ??????          => www[.]hsylc888[.]com
```

## The C2
```
Domain: 
37ole7no82xtgse[.]icu
                       \
                        same cert, same IP
                       /
ryh0o60i5lem3xs[.]icu
```
```
IP: 
                   UTC+8 20:26
54.254.139[.]54 -> 3.0.239[.]81
```

## Shell Companies
shebvb[.]cn

dzhkfz[.]cn

sddfgth[.]top

zxcmnbd[.]top

hsykfz[.]cn

~~wtyubz[.]top~~

wewrt[.]top

ajhsftee[.]top
