#!/bin/bash

echo "# Images"

echo ""

echo "<ul>"

for file in lux-items/*.png; do
    echo "<li><img src=\"$file\" alt=\"${file##*/}\"></li>"
done

echo "</ul>"
