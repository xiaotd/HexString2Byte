Hex.java 

byte与16进制字符串快速转换工具类

使用方式：

    byte2HexString
    String hexStr = Hex.Byte2Hex(new byte[]{0x00,0x11,0xFF})
 
    hexString2Byte:
    byte[] bytes = Hex.hex2Byte("0x0011FF")  
    byte[] bytes = Hex.hex2Byte("0x00 11 FF ;hexString")
    
