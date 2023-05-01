#!/bin/bash
echo "# Images"
echo ""
echo "<ul>"
for file in ./*.png; do
    echo "<li><img src=\"$file\" alt=\"${file##*/}\"></li>"
done
echo "</ul>"
