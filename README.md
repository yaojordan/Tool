# Tool
懶人專用

#!/bin/bash

if [ $# -ne 1 ]; then  
	echo "usage: $0 filename"  	
else  
	touch $1.sh  	
	echo "#!/bin/bash" >> $1.sh  	
fi  
