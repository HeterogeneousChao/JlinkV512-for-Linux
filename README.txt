This is a Jlink tool to upload bootloader to Nake ARM board

	usage:   
		exec device = STM32F427VI
		loadbin /src.bin addr(typical: 0x08000000) 
				 		 // this addr define at bootloader seg define
		speed 12000 	 		 // for set the speed
		r				 // for Reset target
		g  		 		 // for go
		h  		 		 // for halt
		setpc addr      		 // for set PC register
		mem   assr NumBytes(hex)	 //for read memory
		
		
						
							ZHAOCHAO
								2016-6-30
		
