
#!/bin/bash


echo "أدخل المبلغ:"
read p


echo "أدخل معدل الفائدة:"
read r


echo "أدخل الزمن (بالسنوات):"
read t


si=$((p * r * t / 100))


echo "الفائدة البسيطة هي: $si"


