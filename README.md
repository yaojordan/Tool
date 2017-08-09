# Tool
懶人專用

#!/bin/bash

if [ $# -ne 1 ]; then  
	echo "usage: $0 filename"  
else  
	touch $1.sh  
	echo "#!/bin/bash" >> $1.sh  
fi    



#!/bin/bash


touch $1.cpp
echo "#include <stdio.h>" >> $1.cpp
echo "#include <stdlib.h>" >> $1.cpp
echo "int main(void){}" >> $1.cpp
