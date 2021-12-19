# steghide

1. Hide data and also decrypt data. Commonly used to hide text message inside image files(jpeg format), Sometimes data can be hidden in audio files too(ex:wav).
2. Commands
   1. steghide command \[ arguments ]
   2. steghide extract -sf input\_file -p password
   3. steghide embed -cf input_file -ef Text_file_to_hide
   4. steghide extract -sf inputfile -xf hiddenfiletoextract
   5. steghide info inputfile
