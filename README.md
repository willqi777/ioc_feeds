# ioc_feeds
# Threat Intelligence Test Project

## Purpose
This project is for **testing and educational purposes only**. It is not intended for real-world use or deployment. The goal is to explore threat intelligence concepts and tools in a controlled environment.

##suricata rule
alert ip any any -> any any (msg:"Detected file with known malicious hash (SHA256, SHA1, or MD5)"; filesha256:filehash_sha256.list; filesha1:filehash_sha1.list; filemd5:filehash_md5.list; filestore; sid:1700001; rev:1;)

## Disclaimer
This project is provided "as-is" without any warranties. Use it at your own risk. The author is not responsible for any misuse or damages caused by this project.

## License
This project is licensed under the [MIT License](LICENSE).
