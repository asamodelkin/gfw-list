cat gfwlist.txt | base64 -d > gfwlist_txt.txt

cat gfwlist_txt.txt | base64 > gfwlist.txt

git add --all && git commit -a && git push
