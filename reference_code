import maya.cmds as mc

def removeUnloadedRef():
	
	referencePresent = mc.file(q=1,reference=1)
	# print referencePresent
	
	if len(referencePresent):
		
		
		for i in range(len(referencePresent)):
			
			
			if not mc.referenceQuery(referencePresent[i],isLoaded=1):
				
				
				mc.file(referencePresent[i],rr=1)
				
				
removeUnloadedRef()
