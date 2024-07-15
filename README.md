### Edit list
cat gfwlist.txt | base64 -d > gfwlist_txt.txt

cat gfwlist_txt.txt | base64 > gfwlist.txt

git add --all && git commit -a && git push

### Check
curl http://localhost:1089/proxy.pac | head -n40

