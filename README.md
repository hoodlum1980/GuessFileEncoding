# GuessFileEncoding
To detect and guess a text-file's encoding (UTF8, UTF16 LE, GBK / GB2312 for simplified Chinese). If the BOM is present, then we trust the BOM, if BOM is absent, then we guess encoding by check characters one by one from file's begining.
