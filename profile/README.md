# ITS Laboratory, Kyushu
## Secret Sharing

This project aims to develop a cloud datastore service based on secret sharing.

Cloud datastore services are essential for accessing your data from anywhere. However, they still carry risks of data leakage, as cloud services occasionally become targets of malicious attackers, and of data loss, since the hardware of each cloud service occasionally breaks down. To solve this problem, we've developed a cloud datastore service that employs a brand-new secret sharing scheme to distribute your data across several cloud services and physical locations around the world.

Our secret sharing scheme ensures that attackers who crack only some cloud services cannot reveal your data, and your data will not be lost even if some data centers are damaged, since your data are stored around the world.

### Softwares
* [Our closs-group secret sharing based key-value datastore](https://itslab-kyushu.github.io/cgss/)
* [Shamir's secret sharing based key-value datastore](https://itslab-kyushu.github.io/sss/)
* [Simple key-value datastore \(to compare performance\)](https://itslab-kyushu.github.io/simple-kvs/)

### Publications
* [Hiroaki Anada](https://sites.google.com/view/lab-hiroaki-anada/), Takanori Yasuda, [Junpei Kawamoto](https://www.jkawamoto.info/), Jian Weng, KouichiSakurai, “[RSA public keys with inside structure: Proofs of key generation and identities for web-of-trust](https://www.sciencedirect.com/science/article/abs/pii/S2214212617303563),” Journal of Information Security and Applications, vol.45, pp.10-19, April 2019.
* [Hiroaki Anada](https://sites.google.com/view/lab-hiroaki-anada/), [Junpei Kawamoto](https://www.jkawamoto.info/), Chenyutao Ke, [Kirill Morozov](https://engineering.unt.edu/people/kirill-morozov.html), and Kouichi Sakurai, “[Cross-Group Secret Sharing Scheme for Secure Usage of Cloud Storage over Different Providers and Regions](http://www.anrdoezrs.net/links/8186671/type/dlg/https://link.springer.com/article/10.1007%2Fs11227-017-2009-7),” [The Journal of Supercomputing](http://www.anrdoezrs.net/links/8186671/type/dlg/https://link.springer.com/journal/11227), 2017.
* Chenyutao Ke, [Hiroaki Anada](https://sites.google.com/view/lab-hiroaki-anada/), [Junpei Kawamoto](https://www.jkawamoto.info/), [Kirill Morozov](https://engineering.unt.edu/people/kirill-morozov.html), and Kouichi Sakurai, “[Cross-group Secret Sharing for Secure Cloud Storage Service](http://hdl.handle.net/2324/1563374),” Proc. of the Annual International Conference on Ubiquitous Information Management and Communication (IMCOM 2016), pp.63:1-63:8, Vietnam, Jan.4-6, 2016.

## Cyberbullying
Scraping comments from YouTube. This tool collects comments to make a dataset for detecting cyberbullying comments.

### Softwares
* [Scraping comments from Youtube](https://itslab-kyushu.github.io/youtube-comment-scraper/)
* [Crawling Youtube comments](https://itslab-kyushu.github.io/youtube-comment-crawler/)

### Publications
* Ziyi Li, [Junpei Kawamoto](https://www.jkawamoto.info/), [Yaokai Feng](http://stap.ait.kyushu-u.ac.jp/~fengyk/index-e.html), and Kouichi Sakurai, “Cyberbullying Detection Using Parent-Child Relationship between Comments,” Proc. of the 18th International Conference on Information Integration and Web-based Applications & Services (iiWAS2016), Singapore, Nov. 23-30, 2016.
