#!/bin/bash

location="./Downloads/"
link="https://raw.githubusercontent.com/xpams/UIView-Blur/master/README.md"
README="README.md"

wget -P "$location" "$link"

echo "The file was downloaded to $location folfer"

tail -n 11 "$location$README"
