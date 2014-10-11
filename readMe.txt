1. Put jar file to project libs.
2. Device need a root
3. import r.b.adbconnect.ADBtcp;
4. Use ADBtcp.getADBstate(), ADBtcp.onADB(), ADBtcp.offADB();

Example:

	if (ADBtcp.getADBstate() == false) {

		ADBtcp.onADB();

	} else {

		ADBtcp.offADB();
	}
        
