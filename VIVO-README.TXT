1. Change project version:

for x in $(grep -l -R 0.8.0.vivo_1 *); do sed -i -e 's/0.8.0.vivo_1/0.8.0.vivo_1/g' $x; done;
