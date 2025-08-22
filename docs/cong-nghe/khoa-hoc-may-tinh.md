# Khoa học máy tính

(Bản dịch Tiếng Việt gốc của Đạt Hoàng, mình chỉ thêm một số các nguồn tài nguyên học bằng Tiếng Việt, chương trình tự học Tiếng Anh cho dân học KHMT với chỉnh sửa bản dịch)

Nếu bạn là kỹ sư phần mềm tự học hoặc học từ bootcamp, bạn thực sự nợ chính mình một nền tảng Khoa học máy tính vững chắc. May mắn thay, bạn không cần phải dành nhiều năm trời hay đổ một đống tiền 💸 vào đại học để có được điều đó.

Tài liệu thì đầy rẫy ngoài kia, nhưng không phải cái nào cũng đáng thời gian. Bạn không cần thêm một danh sách “200+ khóa học miễn phí online” nữa. Điều bạn cần là câu trả lời cho những câu hỏi sau:

* **Học những môn nào**, và vì sao?
* Với mỗi môn, **cuốn sách hoặc series video nào tốt nhất**?

Bản hướng dẫn này là nỗ lực của chúng tôi nhằm trả lời dứt khoát hai câu hỏi đó.

Hãy học cả 9 môn dưới đây, theo thứ tự gợi ý, bằng **sách giáo trình hoặc video**, lý tưởng nhất là cả hai. Mỗi môn nên đầu tư khoảng **100–200 giờ**, rồi sau này quay lại ôn tập khi cần – suốt cả sự nghiệp của bạn 🚀.

<!-- | Chủ đề | Lý do cần học | Sách | Video bài giảng |
| :------ | :--------- | :--- | :----- |
| [Tiếng Anh](#tiếng-anh) | Việc học Tiếng Anh là điều bắt buộc cho việc học Khoa học máy tính hay trong thế giới hiện đại | Không giới hạn | Không giới hạn |
| **[Lập trình](#lập-trình)**| Đừng là người “chưa bao giờ hiểu rõ” về một thứ như đệ quy.|*Cấu trúc và diễn giải các chương trình máy tính*|Brian Harvey's Berkeley CS 61A|
|**[Kiến trúc máy tính](#kiến-trúc-máy-tính)**|Nếu bạn không có nền tẳng vững chắc về cách máy tính thực sự hoạt động, tất cả các bản abstraction cao hơn của bạn sẽ trở nên không mạch lạc.|*Hệ thống máy tính: Góc nhìn của một lập trình viên*|Berkeley CS 61C|
|**[Thuật toán và cấu trúc dữ liệu](#thuật-toán-và-cấu-trúc-dữ-liệu)**| Nếu bạn không biết cách sử dụng cấu trúc dữ liệu phổ biến như ngăn xếp, hàng đợi, cây, và đồ thị, bạn sẽ không có thể giải quyết các vấn đề khó.|*Hướng dẫn Thiết kế Thuật toán*|Bài giảng của Steven Skiena|
|**[Toán cho KHMT](#toán-học-cho-khoa-học-máy-tính)**| KHMT về cơ bản là một nhánh của toán học ứng dụng, vì vậy học toán sẽ mang lại cho bạn lợi thế cạnh tranh.|*Toán học cho Khoa học Máy tính*|MIT 6.042J của Tom Leighton|
|**[Hệ điều hành](#hệ-điều-hành)**| Hầu hết các đoạn mã bạn viết được chạy bởi một hệ điều hành, vì vậy bạn nên biết chúng tương tác như thế nào.|*Hệ điều hành: Ba mảnh dễ dàng*|Berkeley CS 162|
|**[Mạng máy tính](#mạng-máy-tính)**|Internet là một vấn đề lớn: bạn cần hiểu cách nó hoạt động để khai thác hết tiềm năng của nó.|*Mạng máy tính: một cách tiếp cận từ tầng trên xuống dưới*|Stanford CS 144|
|**[Cơ sở dữ liệu](#cơ-sở-dữ-liệu)**|Dữ liệu là trọng tâm của hầu hết các chương trình quan trọng, nhưng ít người hiểu cách hệ thống cơ sở dữ liệu thực sự hoạt động.|*Đọc trong Hệ thống Cơ sở Dữ liệu*|Joe Hellerstein's Berkeley CS 186|
|**[Ngôn ngữ và Trình biên dịch](#ngôn-ngữ-và-trình-biên-dịch)**|Nếu bạn hiểu cách ngôn ngữ và trình biên dịch thực sự hoạt động, bạn sẽ viết mã tốt hơn và học ngôn ngữ mới dễ dàng hơn.|*Tạo thông dịch viên*|Khóa học của Alex Aiken trên edX|
|**[Hệ thống phân tán](#hệ-thống-phân-tán)**|Ngày nay, *hầu hết* hệ thống là phân tán.|*Thiết kế các ứng dụng chuyên sâu về dữ liệu* của Martin Kleppmann|MIT 6.824| -->

### Quá nhiều?

Nếu nghĩ tới việc tự học 9 môn trong nhiều năm khiến bạn muốn bỏ cuộc, thì hãy bắt đầu với **hai cuốn sau**:

* *Computer Systems: A Programmer's Perspective*
* *Designing Data-Intensive Applications*

Theo kinh nghiệm của chúng tôi, đây là hai cuốn “đáng đồng tiền bát gạo” nhất cho dân tự học hoặc học bootcamp, đặc biệt nếu bạn đang làm việc với ứng dụng mạng. Chúng cũng có thể trở thành “thuốc dẫn” để bạn khám phá các chủ đề còn lại.

### Vì sao nên học Khoa học máy tính?

Có **hai kiểu kỹ sư phần mềm**:

* Loại **hiểu rõ khoa học máy tính**, có thể tạo ra giải pháp sáng tạo và chất lượng
* Và loại **chỉ biết dùng công cụ**, làm việc ở mức bề mặt

Cả hai đều gọi mình là kỹ sư phần mềm, và lúc mới vào nghề, lương có thể ngang nhau. Nhưng theo thời gian, loại 1 sẽ tiến tới những công việc thỏa mãn và có giá trị hơn – dù là công việc thương mại hay dự án mã nguồn mở, vai trò lãnh đạo kỹ thuật hay cá nhân xuất sắc.

Loại 1 luôn tìm cách học KHMT sâu sắc – dù là đi học chính quy hay tự học suốt đời. Loại 2 thường chỉ học thứ đang “thịnh hành”, không mấy khi đụng tới gốc rễ của vấn đề.

Hiện tại, số người đổ vào ngành đang tăng nhanh, nhưng số sinh viên tốt nghiệp CS thì gần như không đổi. Sự thừa mứa kỹ sư loại 2 đang khiến cơ hội của họ teo lại, và khó chạm tới những công việc tốt hơn. Nếu bạn muốn trở thành kỹ sư loại 1 – hay ít nhất có công việc ổn định – thì **học khoa học máy tính là con đường duy nhất đáng tin cậy**.

## Hướng dẫn chi tiết cho các chủ đề


### Tiếng Anh

Việc học một ngôn ngữ là cả một quá trình dài. Điều này được viết ra không phải để làm bạn nản lòng, bạn cần phải chấp nhận rằng bạn sẽ phải dành ra rất nhiều thời gian để học ngoại ngữ dù bằng cách nào đi nữa, không có đường tắt nào cả.

Rất nhiều chuyên ngành bây giờ đều đòi hỏi Tiếng Anh ở một mức độ nhất định, nhưng riêng với KHMT thì nó là _rất nhiều_. Khá nhiều lập trình viên đã tự đánh giá rằng mức Tiếng Anh của họ là _đủ đề đọc tài liệu_ nên mình nghĩ là mọi người đều không hoàn toàn mất gốc.

Dành cho những người mà nghĩ mình không biết một chút gì về Tiếng Anh, hãy bắt đầu bằng cách học một chương trình học cơ bản, mình gợi ý chương trình [30 ngày Tiếng Anh](https://daihocmo.github.io/tieng-anh/30ngay/) (Cho những người có thể dành thời gian khoảng ít nhất 2 giờ mỗi ngày cho việc học Tiếng Anh). Bạn có thể chọn bất kì chương trình nào bạn muốn, với một tâm thế rằng bạn dành càng nhiều thời gian thì tốc độ lên trình của bạn càng nhanh.

Bạn cũng cần học về cách học ngoại ngữ nữa, bạn có thể lựa chọn một trong hai hướng dẫn sau:

- [Tự luyện ngoại ngữ](https://daihocmo.github.io/ngoai-ngu/) - Được tổng hợp bởi [Khu học mở](https://daihocmo.github.io/). Trang hướng dẫn cách học ngoại ngữ, cách xây dựng môi trường tự học ngoại ngữ và các bài hướng dẫn khác. Sau đó bạn sẽ đọc trang [Tự luyện Tiếng Anh](https://daihocmo.github.io/tieng-anh/) để đọc hướng dẫn riêng cho Tiếng Anh và truy cập các tài nguyên tự học. Các bài đọc sẽ khá dài nhưng sẽ giúp bạn xây dựng phương pháp tự học ngoại ngữ và định hướng tự học hàng ngày.
- [Mình đã tự học tiếng Anh như thế nào? (Hướng dẫn chi tiết)](https://voz.vn/t/minh-%C4%91a-tu-hoc-tieng-anh-nhu-the-nao-huong-dan-chi-tiet.723117/) - Hướng dẫn của bác [heiji_hattori](https://voz.vn/u/heiji_hattori.1475001/) trên Voz.

Bạn sẽ học Tiếng Anh song song với việc học *Khoa học máy tính*. Việc học Tiếng Anh sẽ không bao giờ có điểm dừng vì *bạn càng học, bạn càng giỏi*, nhưng chắc chắn sẽ đến một mức mà bạn có thể học thông qua những cuốn sách chất lượng bậc nhất bằng Tiếng Anh như SICP (2nd Edition, sử dụng Scheme) hay CS:APP.

### Lập trình

Hầu hết các chương trình đại học cho ngành KHMT đều bắt đầu với phần “giới thiệu” về lập trình máy tính. Các khóa học tốt nhất cho chủ đề này không chỉ giúp cho người mới học, mà còn rất tốt chho những người đã bỏ lỡ các khái niệm và mô hình lập trình khi họ mới học viết mã.

Gợi ý chung nhất của chúng tôi cho nội dung này là cuốn sách kinh điển *Cấu trúc và diễn giải các chương trình máy tính* (SICP - viết tắt tên tiếng Anh). Nó được cung cấp trực tuyến miễn phí dưới dạng [sách điện tử](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html), và dưới dạng một tập hợp [các bài giảng video của MIT](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/). Mặc dù những bài giảng đó rất hay, nhưng đề xuất video của chúng tôi là [bài giảng SICP của Brian Harvey](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter) (cho khóa học 61A tại Berkeley). Các bài giảng này được trau chuốt hơn và hướng đến đối tượng là sinh viên mới tốt hơn so với các bài giảng của MIT.

Hoặc nếu không, bạn có thể bắt đầu bằng khóa [CS50 Vietsub](https://www.youtube.com/playlist?list=PLJ3cEjfn1AKRdtE2KNLCw0sgBfdmAeulI) trên Youtube.

Chúng tôi khuyên bạn nên học qua ít nhất ba chương đầu tiên của SICP và làm các bài tập. Để thực hành thêm, hãy thử giải quyết một loạt các bài tập về lập trình nhỏ trên [exercism.io](http://exercism.io/).

SICP có khả năng thay đổi (dù ít hay nhiều) suy nghĩ nền tảng của bạn về máy tính và lập trình. Không phải ai cũng sẽ cảm nhận được điều này. Nhưng giá trị tiềm năng mà nó mang lại vẫn đáng để bỏ thời gian ra đọc.

Cuối cùng, một điểm cần làm rõ: hướng dẫn này KHÔNG được viết ra cho những người hoàn toàn mới học lập trình. Chúng tôi giả định rằng bạn là một lập trình viên có năng lực mà không có nền tảng về KHMT, đang tìm cách lấp đầy một số lỗ hổng kiến ​​thức. Thực tế là chúng tôi đặt ra một chủ đề về "lập trình" chỉ đơn giản là một lời nhắc nhở rằng bạn có thể cần tìm hiểu nhiều hơn nữa. Đối với những người chưa bao giờ viết mã trước đây, nhưng nếu muốn, bạn có thể thích một hướng dẫn như [cái này](https://www.reddit.com/r/learnprogramming/wiki/faq#wiki_getting_started).

[![Cấu trúc và diễn giải các chương trình máy tính](./images/sicp.jpg)](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html)

### Kiến trúc máy tính

"Kiến trúc máy tính" là học phần đầu tiên giúp bạn hiểu cách máy tính hoạt động ở tầng sâu hơn bên dưới phần mềm. Theo kinh nghiệm của chúng tôi, đây là mảng thường bị bỏ sót nhất đối với các kỹ sư phần mềm tự học.

Cuốn sách nhập môn được gợi ý là *Computer Systems: A Programmer's Perspective*. Một khóa học nhập môn dựa trên sách này thường bao gồm các chương 1–6, cung cấp nền tảng quan trọng về cách máy tính thực sự vận hành.

Điều chúng tôi đánh giá cao ở **CS\:APP** là cách tiếp cận thực tiễn, tập trung vào góc nhìn của lập trình viên. Dù kiến trúc máy tính hiện đại còn rộng lớn hơn nhiều so với nội dung trong sách, CS\:APP vẫn là một điểm khởi đầu tuyệt vời nếu bạn muốn hiểu sâu về hệ thống để viết phần mềm **nhanh hơn, hiệu quả hơn và đáng tin cậy hơn**.

Nếu bạn muốn một cách tiếp cận nhẹ nhàng hơn, đồng thời cân bằng giữa phần cứng và phần mềm, thì chúng tôi gợi ý cuốn *The Elements of Computing Systems*, thường được gọi là “Nand2Tetris”. Đây là một cuốn sách đầy tham vọng, giúp bạn hình dung tổng thể mọi thứ bên trong một máy tính. Mỗi chương dẫn bạn xây từng thành phần nhỏ – từ cổng logic đơn giản, đến CPU, bộ hợp dịch (assembler), rồi đến ứng dụng hoàn chỉnh như trò chơi Tetris.

Chúng tôi khuyên bạn nên đọc ít nhất sáu chương đầu và thực hành các dự án đi kèm. Bạn sẽ hiểu được mối liên hệ giữa kiến trúc phần cứng và phần mềm chạy trên đó.

Nửa đầu cuốn sách và toàn bộ các bài tập thực hành đều có **miễn phí** tại [trang Nand2Tetris](http://www.nand2tetris.org). Ngoài ra, bạn có thể học qua khóa học Coursera kèm theo video giảng dạy tại [đây](https://www.coursera.org/learn/build-a-computer).

Tất nhiên, vì ưu tiên tính đơn giản và tổng quan, **Nand2Tetris** không đào sâu một số chủ đề quan trọng trong kiến trúc hiện đại như: **pipeline** (xử lý theo luồng) và **memory hierarchy** (phân cấp bộ nhớ).

Sau khi hoàn thành khóa Nand2Tetris, có thể quay trở lại cuốn CS:APP, hoặc cuốn *Computer Organization and Design* của Patterson và Hennessy – một tác phẩm kinh điển trong lĩnh vực này. Không phải mọi phần trong sách đều cần thiết; chúng tôi khuyên bạn nên theo dõi [khóa học CS61C của Berkeley](http://inst.eecs.berkeley.edu/~cs61c/sp15/) “Những ý tưởng tuyệt vời trong kiến ​​trúc máy tính” để có thể đọc cụ thể. Các ghi chú bài giảng và phòng thử nghiệm  được cung cấp trực tuyến, và các bài giảng trước đây có thể xem trên [Internet Archive](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_). 

Một khóa học hiếm hoi mà mình tìm được bằng Tiếng Việt là khóa IT3030. Các tài nguyên hỗ trợ việc học IT3030:

- Giáo trình: [Computer Organization And Design](https://archive.org/details/computer-organization-and-design-fifth-edition-the-hardware-software-interface-by-hennessy)
- Khóa học: [Kiến trúc máy tính (IT3030) - SOICT HUST](https://www.youtube.com/playlist?list=PL54DF7EQeBp6a3T4DBIIZrqCzmMoRgvbK)
- [Slide bài giảng](https://tailieuhust.com/tai-lieu-mon-kien-truc-may-tinh-hust/)
- [Thông tin thêm về khóa học cũng như các nguồn tài nguyên](http://dce.hust.edu.vn/kien-truc-may-tinh/)

[![Hệ thống máy tính: Góc nhìn của một lập trình viên](./images/csapp.jpg)](http://csapp.cs.cmu.edu/3e/home.html)

> Phần cứng là nền tảng
> 
> Mike Acton, Giám đốc kỹ thuật tại Insomniac Games
>
> ([xem buổi talk tại CppCon của ông](https://www.youtube.com/watch?v=rX0ItVEVjHc))

### Thuật toán và cấu trúc dữ liệu

Chúng tôi đồng ý với sự đồng thuận chung trong nhiều thập kỷ rằng sự quen thuộc với các thuật toán và cấu trúc dữ liệu phổ biến là một trong những đặc điểm có nhiều ý nghĩa nhất của chương trình giáo dục khoa học máy tính. Đây cũng là một nơi tuyệt vời để đào tạo khả năng giải quyết vấn đề chung của một người, khả năng này sẽ mang lại hiệu quả trong mọi lĩnh vực nghiên cứu khác.

Có hàng trăm cuốn sách ngoài kia, nhưng cuốn sách yêu thích của chúng tôi là *[Hướng dẫn Thiết kế Thuật toán](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/)* của Steven Skiena. Tác giả rõ ràng yêu thích việc giải quyết vấn đề bằng thuật toán và thường thành công trong việc nuôi dưỡng sự nhiệt tình tương tự giữa các sinh viên và độc giả của mình. Theo ý kiến ​​của chúng tôi, hai cuốn sách được nhiều gợi ý hơn (CLRS và Sedgewick) có xu hướng hơi quá nặng theo hướng chứng minh cho những người chủ yếu học lý thuyết đẻ giúp họ giải quyết vấn đề thực tế.

Đối với những bạn thích các bài giảng video, [Skiena hào phóng cung cấp phiên bản trực tuyến](https://www.youtube.com/watch?v=A2bFN3MyNDA&list=PLOtl7M3yp-DX32N0fVIyvn7ipWKNGmwpp). Chúng tôi cũng thực sự thích khóa học của Tim Roughgarden ở[trên Coursera](https://www.coursera.org/specializations/algorithm) và [nơi khác](http://timroughgarden.org/videos.html). Cho dù bạn thích phong cách giảng bài của Skiena hay Roughgarden đều ổn, đấy chỉ là sở thích cá nhân. Trên thực tế, có hàng tá lựa chọn thay thế cũng rất tốt, vì vậy nếu bạn tình cờ tìm thấy nguồn tài liệu khác mà bạn thích, chúng tôi khuyến khích bạn tiếp tục với nguồn tài liệu đó!

Để thực hành, chúng tôi gợi ý giải các bài toán trên [Leetcode](https://leetcode.com/). Chúng là những vấn đề thú vị với các giải pháp và thảo luận đi kèm. Họ cũng giúp bạn kiểm tra sự tiến bộ so với các câu hỏi thường được sử dụng trong các cuộc phỏng vấn kỹ thuật tại các công ty phần mềm cạnh nổi tiếng. Chúng tôi khuyên bạn nên giải quyết khoảng 100 bài toán leetcode ngẫu nhiên như một phần của việc nghiên cứu và học tập. 

Cuối cùng, chúng tôi đề xuất cuốn sách *[Cách giải quyết](https://smile.amazon.com/How-Solve-Mathelogical-Princeton-Science/dp/069116407X/)* như một hướng dẫn tuyệt vời và độc đáot liên quan tới giải quyết vấn đề nói chung; nó hữu dụng cho khoa học máy tính cũng như toán học.

[![Hướng dẫn Thiết kế Thuật toán](./images/skiena.jpg)](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/) [![Cách giải quyết](./images/polya.jpg)](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/)

> Tôi chỉ có một phương pháp mà tôi đề xuất rộng rãi. Đó là suy nghĩ trước khi bạn viết.
>
> Richard Hamming

### Toán học cho Khoa học Máy tính

Theo một cách nào đó, khoa học máy tính là một nhánh của toán học ứng dụng đã phát triển quá nhanh. Mặc dù nhiều kỹ sư phần mềm cố gắng bỏ qua chủ đề này ở các mức độ khác nhau, chúng tôi khuyến khích bạn nắm bắt nó bằng cách nghiên cứu trực tiếp. Nếu học được thành công sẽ mang lại cho bạn một lợi thế cạnh tranh to lớn so với những người không học.

Lĩnh vực toán học có liên quan nhất đối với KHMT được gọi rộng rãi là “toán học rời rạc”, trong đó “rời rạc” đối lập với “liên tục” và là một tập hợp các chủ đề toán học ứng dụng thú vị ngoài giải tích. Với định nghĩa mơ hồ như vậy, sẽ không có nhiều ý nghĩa nếu cố gắng học mọi thứ về “toán học rời rạc. Một mục tiêu thực tế hơn là xây dựng sự hiểu biết về logic, tổ hợp và xác suất, lý thuyết tập hợp, lý thuyết đồ thị, và một chút lý thuyết số thông báo về mã hoá. Đại số tuyến tính là một lĩnh vực đáng nghiên cứu bổ sung, do tầm quan trọng của nó trong đồ họa máy tính và học máy.

Điểm bắt đầu mà chúng tôi đề xuất cho toán học rời rạc là tập hợp [các ghi chú bài giảng của László Lovász](http://www.cs.elte.hu/~lovasz/dmbook.ps). Giáo sư Lovász đã làm rất tốt việc làm cho nội dung dễ tiếp cận và trực quan, vì vậy đây là điểm khởi đầu tốt hơn so với tài liệu chính thức.

Để có hiểu sâu hơn, chúng tôi đề xuất *[Toán học cho Khoa học Máy tính](https://courses.csail.mit.edu/6.042/spring17/mcs.pdf)*, ghi chú bài giảng dài như sách cho khóa học ở MIT có cùng tên gọi. Video bài giảng của khóa học đó cũng [miễn phí](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/), và là video bài giảng chúng tôi khuyên dùng cho môn toán rời rạc.

Đối với đại số tuyến tính, chúng tôi khuyên bạn nên bắt đầu với loạt video [Bản chất của đại số tuyến tính](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab), theo sau là [sách của Gilbert Strang](https://www.amazon.com/Introduction-Linear-Algebra-Gilbert-Strang/dp/0980232775/) và [video bài giảng](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/).

> Nếu mọi người không tin rằng toán học là đơn giản, đó chỉ là vì họ không nhận ra cuộc sống phức tạp như thế nào.
> 
> John von Neumann

Học Toán bằng Tiếng Việt (*sẽ khá là chán...*)

Điểm bắt đầu mà chúng tôi đề xuất cho toán học rời rạc là [Giáo trình toán rời rạc - Tổ hợp và đồ thị](http://math.ac.vn/training/images/TTDaotao/VinIF/Toanroirac_NHThach.pdf) của Nguyễn Hoàng Thạch.

Nếu bạn muốn tìm hiểu sâu hơn, thì cá nhân mình gợi ý  cuốn [GIÁO TRÌNH TOÁN RỜI RẠC của NGUYỄN ĐỨC NGHĨA và NGUYỄN TÔ THÀNH](https://users.soict.hust.edu.vn/sangdv/TRR_NguyenDucNghia.pdf). Về video bài giảng thì mình gợi ý danh sách phát [Toán rời rạc của TITV](https://www.youtube.com/playlist?list=PLyxSzL3F7486CtfXZXj3YSgmnWHvNUol8)

Đối với đại số tuyến tính, bạn có thể xem danh sách phát [Đại số tuyến tính của Giang Le](https://www.youtube.com/playlist?list=PL5g_dfwUnO84IehDgeDlXbwd0pLzhTWSZ) hoặc đọc cuốn [Giáo trình đại số Tuyến tính](https://cuuduongthancong.com/pvf/582841/dai-so-tuyen-tinh/bui-xuan-dieu/bai-giang-dai-so-tuyen-tinh---bui-xuan-dieu.pdf) của Bùi Xuân Diệu.

Mình không thấy TeachYourselfCS đề cập đến Toán cao cấp, nhưng nếu bạn muốn học Toán cao cấp nữa thì có thể sử dụng 3 cuốn [Giáo trình toán cao cấp](https://tailieuvnu.com/giao-trinh-toan-cao-cap-tap-1/) được biên soạn bởi Nguyễn Đình Trí, Tạ Văn Đĩnh và Nguyễn Hồ Quỳnh.

### Hệ điều hành

*[Khái niệm hệ điều hành](https://www.amazon.com/dp/1118063333/)* và *[Hệ điều hành hiện đại](https://www.amazon.com/dp/013359162X/)* là những cuốn sách “kinh điển” về hệ điều hành. Cả hai đều bị chỉ trích vì sự thiếu rõ ràng và không thân thiện với học sinh.

*Hệ điều hành: Ba mảnh dễ dàng* là một thay thế tốt, được xuất bản [trực tuyến và miễn phí](http://pages.cs.wisc.edu/~remzi/OSTEP/). Chúng tôi đặc biệt thích cấu trúc và tính dễ đọc của cuốn sách và cảm thấy rằng các bài tập rất đáng giá.

Sau *Hệ điều hành: Ba mảnh dễ dàng*, chúng tôi khuyến khích bạn khám phá các quyết định thiết kế của các hệ điều hành cụ thể, thông qua các cuốn sách kiểu “Phía trong của {Tên hệ điều hành}" chẳng hạn như *[Bài bình luận của Lion về Unix](https://www.amazon.com/Lions-Commentary-Unix-John/dp/1573980137/)*, *[Thiết kế và triển khai hệ điều hành FreeBSD](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972/)* và *[Phía trong của Mac OS X](https://www.amazon.com/Mac-OS-Internals-Systems-Approach/dp/0321278542/)*. Đối với Linux, chúng tôi đề xuất cuốn sách tuyệt vời [Phát triển nhân Linux](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468) của Robert Love.

Một cách rất tốt để củng cố sự hiểu biết của bạn về hệ điều hành là đọc mã của một hạt nhân nhỏ và thêm các tính năng. Một lựa chọn là [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html), một phiên bản từ Unix V6 sang ANSI C và x86, nó được duy trì cho một khóa học tại MIT. *Hệ điều hành: Ba mảnh dễ dàng* có một phụ lục về tiềm năng của [xv6 labs](http://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf), trong đó nêu ra những ý tưởng tuyệt vời cho các dự án tiềm năng.

Tiếng Việt: [GIÁO TRÌNH HỆ ĐIỀU HÀNH (OPERATING SYSTEM)](https://www.rachbauer-kran.at/wp-content/uploads/2015/10/BG_HDH.pdf) được biên soạn bởi Ninh Xuân Hải và Huỳnh Trọng Thưa. Về video bài giảng, bạn có thể xem [Nguyên lý hệ điều hành (IT3070) - SOICT HUST](https://www.youtube.com/playlist?list=PL54DF7EQeBp605B_-ECoKaKo2yEA5Fby5)

[![Hệ điều hành: Ba mảnh dễ dàng](./images/ostep.jpeg)](http://pages.cs.wisc.edu/~remzi/OSTEP/)

### Mạng máy tính

Thực tế hiện nay có rất nhiều kỹ thuật phần mềm nằm trên máy chủ web và máy khách, nên một trong những lĩnh vực có giá trị tức thì của khoa học máy tính là mạng máy tính. Các sinh viên tự học của chúng tôi, những người nghiên cứu mạng máy tính một cách có phương pháp thấy rằng cuối cùng họ cũng hiểu các thuật ngữ, khái niệm và giao thức mà họ đã nhìn thấy trong trong nhiều năm.

Cuốn sách yêu thích của chúng tôi về chủ đề này là *[Mạng máy tính: một cách tiếp cận từ tầng trên xuống dưới](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)*. Các dự án và bài tập nhỏ trong cuốn sách rất đáng để làm, và chúng tôi đặc biệt thích “Phòng thí nghiệm Wireshark” mà họ [cung cấp trực tuyến miễn phí](http://www-net.cs.umass.edu/wireshark-labs/).

Đối với những người thích các bài giảng video, chúng tôi đề xuất [*Khóa học Giới thiệu về Mạng Máy tính*](https://www.youtube.com/playlist?list=PLvFG2xYBrYAQCyz4Wx3NPoYJOFjvU7g2Z) đã được cung cấp trên nền tảng MOOC Lagunita của trường Standford nhưng đáng buồn là bây giờ chỉ có sẵn dưới dạng không chính thức trên Youtube.

Tiếng Việt: Bạn có thể đọc *[BÀI GIẢNG MẠNG MÁY TÍNH](https://github.com/huyinit/MMT-PTIT/blob/main/M%E1%BA%A1ng-m%C3%A1y-t%C3%ADnh-gi%C3%A1o-tr%C3%ACnh.pdf)* được biên soạn bởi ThS. Nguyễn Xuân Anh.

> Bạn không thể nhìn vào quả cầu pha lê và nhìn thấy tương lai. Những gì Internet sẽ trở thành trong tương lai là những gì xã hội tạo ra nó.
> 
> - Bob Kahn

[![Mạng máy tính: một cách tiếp cận từ tầng trên xuống dưới](./images/top-down.jpg)](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)

### Cơ sở dữ liệu

Tự học về hệ thống cơ sở dữ liệu sẽ mất nhiều công sức hơn so với hầu hết các chủ đề khác. Đây là một lĩnh vực nghiên cứu tương đối mới (tức là sau những năm 1970) với những giá trị thương mại lớn cho các ý tưởng tưởng được giữ lại sau các cánh cửa đóng kín. Ngoài ra, nhiều tác giả tiềm năng cho các giáo trình xuất sắc tiềm năng đã muốn tham gia hoặc thành lập các công ty hơn là viết sách.

Trong hoàn cảnh đó, chúng tôi khuyến khích những người tự học nói chung tránh sách giáo khoa và bắt đầu với [các video CS 186](https://www.youtube.com/user/CS186Berkeley/videos), đây là khóa học cơ sở dữ liệu của Joe Hellerstein tại Berkeley, sau đó mới tiến sang đọc giáo trình hay tài liệu khác.

Một tài liệu cụ thể rất đáng đề cập đối với sinh viên mới l [Kiến trúc của một hệ thống cơ sở dữ liệu](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf). Tài liệu này cung cấp một cái nhìn độc đáo nhằm bao quát về cách hệ quản trị cơ sở dữ liệu quan hệ (RDBMS) hoạt động. Nó sẽ là một nền tảng có ích để các bạn nghiên cứu thêm.

*Đọc trong Hệ thống cơ sở dữ liệu*, còn hay được gọi là [cơ sở dữ liệu “Sách đỏ”](http://www.redbook.io/), là một bộ sưu tập các bài viết do Peter Bailis, Joe Hellerstein, và Michael Stonebraker biên soạn và chỉnh sửa. Đối với những người đã đạt ngưỡng vượt qua mức nội dung của CS 186, "Sách đỏ" sẽ là điểm dừng tiếp theo của bạn.

Nếu bạn kiên quyết sử dụng sách giáo trình cho người mới học, chúng tôi đề xuất *[Hệ thống quản lý cơ sở dữ liệu](https://smile.amazon.com/Database-Management-Systems-Raghu-Ramakrishnan/dp/0072465638/)* của Ramakrishnan và Gehrke. Đối với sinh viên có hiểu biết tốt hơn, cuốn sách kinh điển của Jim Gray *[Xử lý giao dịch: Khái niệm và kỹ thuật](https://www.amazon.com/Transaction-Processing-Concept-Techniques-Management/dp/1558601902)* rất đáng giá, nhưng chúng tôi không không khuyến khích sử dụng những tài liệu này ngay từ đầu.

Cuối cùng, mô hình hóa dữ liệu là một khía cạnh bị bỏ quên và không được chú trọng khi dạy về làm việc với cơ sở dữ liệu. Về chủ đề này, chúng tôi đề xuất *[Dữ liệu và Thực tế: Quan điểm vượt thời gian về việc nhận thức và quản lý thông tin trong thế giới không chính xác của chúng ta](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215)*.

Tiếng Việt: [Cơ sở dữ liệu (IT3090) - SOICT HUST](https://www.youtube.com/playlist?list=PL54DF7EQeBp4CLS8efeXphJ0XTjdYa6cc)

[![Đọc trong Hệ thống cơ sở dữ liệu](./images/redbook.jpg)](http://www.redbook.io/) [![Data and Reality](./images/data-reality.jpg)](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215)

### Ngôn ngữ và Trình biên dịch

Hầu hết các lập trình viên học ngôn ngữ, trong khi hầu hết các nhà khoa học máy tính học *về* ngôn ngữ. Điều này mang lại cho nhà khoa học máy tính một lợi thế khác biệt so với lập trình viên, ngay cả trong lĩnh vực lập trình! Kiến thức của họ khái quát; họ có thể hiểu hoạt động của một ngôn ngữ mới sâu hơn và nhanh hơn so với những người chỉ đơn thuần học một ngôn ngữ cụ thể.

Chúng tôi đề xuất cuốn giáo trình tuyệt vời được cung cấp miễn phí trực tuyến *[Crafting Interpreters](https://craftinginterpreters.com/contents.html)* của Bob Nystrom. Nó được tổ chức tốt, mang tính thư giãn cao và rất phù hợp với những người có mục tiêu chính là hiểu rõ hơn về ngôn ngữ và công cụ cho ngôn ngữ của họ. Chúng tôi khuyên bạn nên dành thời gian để giải quyết toàn bộ vấn đề, thử bất kỳ "thách thức" nào mà bạn quan tâm.

Một đề xuất truyền thống hơn là *[Trình biên dịch: Nguyên tắc, Kỹ thuật & Công cụ](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)*, thường được gọi là “Sách Rồng”. Thật không may, nó không được thiết kế để tự học mà để giảng viên chọn ra các chủ đề có giá trị trong từ 1-2 học kỳ cho các khóa học của họ.

Nếu bạn chọn sử dụng "Sách Rồng", điều quan trọng là bạn phải chọn trước các chủ đề, tốt nhất là với sự giúp đỡ của một người cố vấn. Trên thực tế, nhằm khai thác tối đa "Sách Rồng", chúng tôi đề xuất sử dụng nó như là tài liệu tham khảo bổ sung cho một bài giảng video. Đề xuất của chúng tôi cho là [bài giảng video của Alex Aiken trên edX](https://www.edx.org/course/compilers).

[![Trình biên dịch: Nguyên tắc, Kỹ thuật & Công cụ](./images/dragon.jpg)](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)

> Đừng là một lập trình viên dập khuôn. Thay vào đó, hãy xây dựng các công cụ cho người dùng và các lập trình viên khác. Hãy xem lại lịch sử của ngành dệt may và thép: bạn muốn chế tạo máy móc và công cụ, hay bạn muốn vận hành những máy móc đó?

- Ras Bodik nói ở phần mở đầu khóa học trình biên dịch viên của mình

### Hệ thống phân tán

Khi số lượng máy tính tăng lên, chúng cũng *lan rộng*. Trong khi các doanh nghiệp trước đây thường mua các máy tính càng ngày càng lớn hơn, thì giờ đây việc các ứng dụng thậm chí rất nhỏ chạy trên nhiều máy tính cũng rất phổ biến. Hệ thống phân tán là nghiên cứu về các đánh đổi khi sử dụng nó.

Cuốn sách gợi ý của chúng tôi để tự học là của Martin Kleppmann *[Thiết kế các ứng dụng chuyên sâu về dữ liệu](https://smile.amazon.com/Designs-Data-Intensive-Appilities-Reliable-Maintainable-ebook/dp/B06XPJML5D/)*. Cuốn sách này tốt hơn nhiều so với một cuốn sách giáo trình truyền thống, rất dễ đọc, và được thiết kế cho những người thực hành, tránh được việc tìm hiểu quá sâu và học thuật.

Đối với những người tìm kiếm một giáo trình truyền thống hơn hoặc những người muốn tài liệu được cung cấp miễn phí trực tuyến, chúng tôi khuyên bạn nên sử dụng *[Hệ thống phân tán, phiên bản thứ 3](https://www.distributed-systems.net/index.php/books/ds3/)* của Maarten van Steen và Andrew Tanenbaum. 

Đối với những người thích video, một khóa học tuyệt vời với các video trực tuyến là [MIT's 6.824](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB), một khóa học sau đại học do Robert Morris giảng dạy với các bài viết được cung cấp [tại đây](https://pdos.csail.mit.edu/6.824/schedule.html).

Nếu bạn muốn học bằng Tiếng Việt, bạn có thể học theo khóa học IT4611 của Bách Khoa, được dạy bởi Trần Hải Anh nên yên tâm về chất lượng nha:

- [Thông tin toàn bộ khóa học trên trang của giảng viên](https://users.soict.hust.edu.vn/anhth/Courses/DistributedSystems/distributed_systems.html)
- Giáo trình: [Distributed Systems: Principles and Paradigms](https://csc-knu.github.io/sys-prog/books/Andrew%20S.%20Tanenbaum%20-%20Distributed%20Systems.%20Principles%20and%20Paradigms.pdf)
- Video bài giảng: [Các hệ thống phân tán và ứng dụng (IT4611) - SOICT HUST](https://www.youtube.com/playlist?list=PL54DF7EQeBp4e2tCXneoGpXX441jBtg5h)
- [Tài liệu môn](https://tailieuhust.com/tai-lieu-cac-he-thong-phan-tan-va-ung-dung-hust/)
- Example Code: [Example code distributed system IT4611](https://github.com/Yreus6/Distributed-System/)

Bất kể bạn lựa chọn sách giáo trình hay các tài nguyên thứ cấp khác, việc nghiên cứu các hệ thống phân tán đòi hỏi phải đọc các bài viết nghiên cứu liên quan. Bạn có thể tìm hiểu danh sách này [tại đây](http://dsrg.pdos.csail.mit.edu/papers/) và chúng tôi thực sự khuyến khích bạn tham dự một nhóm của [Papers We Love](http://paperswelove.org/) tại khu vực của bạn.

[![Thiết kế các ứng dụng chuyên sâu về dữ liệu](./images/ddia.jpg)](https://smile.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable-ebook/dp/B06XPJML5D/)

Các câu hỏi thường gặp
--------------------------

#### Đối tượng mục tiêu của hướng dẫn này là ai?

Trong suy nghĩ của chúng tôi, bạn là một kỹ sư phần mềm tự học, tốt nghiệp từ bootcamp hoặc học sinh phổ thông có khả năng, hoặc một sinh viên đại học đang tìm cách bổ sung cho chương trình giáo dục chính thức của mình bằng cách tự học. Câu hỏi về thời điểm bắt đầu cuộc hành trình này là một câu hỏi hoàn toàn cá nhân đối với mỗi người, nhưng hầu hết mọi người có xu hướng được hưởng lợi từ việc có một số kinh nghiệm chuyên môn trước khi đi quá sâu vào các lý thuyết KHMT. Ví dụ: chúng tôi nhận thấy rằng sinh viên *thích* học về hệ thống cơ sở dữ liệu nếu họ đã làm việc với cơ sở dữ liệu trong công việc, hoặc về mạng máy tính nếu họ đã làm việc trên một hoặc hai dự án web.

#### AI/graphics/chủ-đề-X thì sao?

Chúng tôi đã cố gắng giới hạn danh sách của mình trong các chủ đề khoa học máy tính mà chúng tôi cảm thấy *mọi kỹ sư phần mềm làm việc thực tế* đều nên biết, bất kể chuyên môn hay ngành cụ thể nào. Theo kinh nghiệm của chúng tôi, đây sẽ là những chủ đề đêm lại hiệu quả cao nhất cho phần lớn các kỹ sư tự học và sinh viên tốt nghiệp bootcamp, đồng thời cung cấp một nền tảng vững chắc để nghiên cứu thêm. Sau đó, bạn sẽ ở một vị trí tốt hơn để chọn sách giáo trình hoặc các nghiên cứu, và học các khái niệm cốt lõi mà không cần hướng dẫn nhiều. Dưới đây là các điểm khởi đầu mà của chúng tôi đề xuất cho một số “môn tự chọn” phổ biến:

- Đối với trí tuệ nhân tạo: học [Khóa học giới thiệu về AI của trường Berkeley](http://ai.berkeley.edu/) bằng cách xem video và hoàn thành các dự án Pacman. Dưới dạng sách giáo trình, hãy sử dụng sách của Russell và Norvig, mang tên *Trí tuệ nhân tạo: Phương pháp tiếp cận hiện đại*.
- Đối với học máy: thực hiện khóa học của Andrew Ng trên Coursera. Hãy kiên nhẫn và đảm bảo rằng bạn hiểu các nguyên tắc cơ bản trước khi bắt đầu với các chủ đề mới hấp dẫn hơn như học sâu.
- Đối với đồ họa máy tính: học [Berkeley's CS 184](http://inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html), và sử dụng tài liệu [Đồ họa máy tính: Nguyên tắc và thực hành](https://www.amazon.com/Computer-Graphics-Principles-Practice-3rd/dp/0321399528) dưới dạng sách giáo trình.

#### Thứ tự được đề xuất nghiêm ngặt đến mức nào?

Trên thực tế, tất cả các chủ thể này có một số lượng trùng lặp đáng kể và liên quan đến nhau. Ví dụ: mối quan hệ giữa toán học rời rạc và thuật toán: học toán trước tiên sẽ giúp bạn phân tích và hiểu các thuật toán của mình sâu hơn, nhưng học thuật toán trước sẽ cung cấp động lực và bối cảnh lớn hơn cho toán học rời rạc. Tốt nhất, bạn nên xem lại cả hai chủ đề này nhiều lần trong suốt sự nghiệp của mình.

Do đó, thứ tự được đề xuất của chúng tôi chủ yếu ở đó để giúp bạn *chỉ việc bắt đầu*... nếu bạn có lý do thuyết phục để chọn một trình tự khác, thì hãy tiếp tục với nó. “Điều kiện tiên quyết” quan trọng nhất theo quan điểm của chúng tôi là: kiến ​​trúc máy tính trước hệ điều hành hoặc cơ sở dữ liệu, mạng và hệ điều hành trước hệ thống phân tán.

#### Hướng dẫn này so với các khoá học Open Source Society hoặc freeCodeCamp thì sao?

Khi hướng dẫn này được viết lần đầu tiên vào năm 2016, [Hướng dẫn phần mềm nguồn mở OSS](https://github.com/open-source-society/computer-science) có quá nhiều chủ đề, đề xuất nhiều tài liệu không tốt cho nhiều chủ đề, và không cung cấp lý do cụ thể về việc tại sao hoặc khía cạnh nào của các khóa học có giá trị. Chúng tôi đã cố gắng giới hạn danh sách các khóa học của mình mà bạn *thực sự nên biết* với tư cách là một kỹ sư phần mềm bất kể chuyên môn của bạn, và giúp bạn hiểu lý do tại sao mỗi khóa học được bao gồm. Trong những năm tiếp theo, "Hướng dẫn phần mềm nguồn mở OSS" đã được cải thiện, nhưng chúng tôi vẫn nghĩ rằng hướng dẫn này của chúng tôi cung cấp một con đường rõ ràng và gắn kết hơn.

freeCodeCamp chủ yếu tập trung vào lập trình, không phải khoa học máy tính. Để biết lý do tại sao bạn có thể muốn học khoa học máy tính, hãy xem lại ở trên. Nếu bạn chưa quen với lập trình, chúng tôi khuyên bạn nên ưu tiên làm điều đó và quay lại hướng dẫn này sau một hoặc hai năm.

#### Còn ngôn ngữ X thì sao?

Học một ngôn ngữ lập trình cụ thể hoàn toàn khác với việc học về một lĩnh vực khoa học máy tính - học một ngôn ngữ sẽ *dễ dàng hơn* và *ít giá trị hơn nhiều*. Nếu bạn đã biết một vài ngôn ngữ, chúng tôi thực sự khuyên bạn chỉ cần làm theo hướng dẫn của chúng tôi và ghép nối giữa ngôn ngữ bạn biết và các khoảng trống kiến thức. Nếu bạn đã học lập trình tốt (chẳng hạn như thông qua *Cấu trúc và diễn giải các chương trình máy tính*), và đặc biệt là nếu bạn đã học trình biên dịch, bạn chỉ sẽ mất hơn một tuần để học những điều cần thiết của một ngôn ngữ mới, sau đó bạn có thể tìm hiểu về các thư viện/công cụ/hệ sinh thái trong công việc.

#### Công nghệ thời thượng X thì sao?

Không có công nghệ đơn lẻ nào là đủ quan trọng để trở thành một phần cốt lõi trong quá trình học tập và tìm hiểu của bạn. Tuy nhiên, thật tuyệt khi bạn rất hào hứng khi tìm hiểu về công nghệ đó. Bí quyết là làm việc từ công nghệ cụ thể, học sang lĩnh vực hoặc khái niệm cơ bản, và tìm hiểu sâu về điều đó trước khi xem công nghệ thời thượng của bạn phù hợp như thế nào với bức tranh lớn hơn.

#### Tại sao bạn vẫn đề xuất SICP?

Bạn hãy nhìn xem. Một số người thấy "Cấu trúc và diễn giải các chương trình máy tính" (SICP) thật sự khó hiểu và đau đầu, đây là một đặc điểm mà rất ít cuốn sách khác có đặc điểm chung. Nếu bạn không thấy thích cuốn sách này, bạn luôn có thể thử một cái gì đó khác và quay lại với SICP sau.

#### Tại sao bạn vẫn giới thiệu cuốn "Sách Rồng"?

"Sách Rồng" vẫn là tài liệu đơn lẻ đầy đủ nhất cho các trình biên dịch. Nó có một đoạn tệ, thường là do nhấn mạnh quá mức vào một số chủ đề không còn phù hợp để đề cập chi tiết ngày nay, chẳng hạn như parsing (phân tích). Vấn đề là, cuốn sách không bao giờ có ý định nghiên cứu từ trang đầu đến trang cuối, mà nó chỉ nhằm cung cấp nguồn tài liệu đầy đủ cho một giảng viên tổng hợp chúng thành một khóa học. Tương tự, một người tự học có thể chọn cuộc lối đi của riêng họ thông qua cuốn sách, hoặc tốt hơn là làm theo những gợi ý mà các giảng viên đã đưa ra trong các tóm tắt khóa học của họ.

#### Làm cách nào để mua sách giáo trình với giá rẻ?

Nhiều sách giáo trình mà chúng tôi đề xuất được cung cấp miễn phí trên mạng, nhờ sự hào phóng của tác giả. Đối với những sách không có, chúng tôi khuyên bạn nên mua các cuốn sách đã qua sử dụng của các phiên bản cũ hơn. Theo nguyên tắc chung, nếu đã có nhiều hơn một vài ấn bản sách giáo trình, thì rất có thể một phiên bản cũ hơn là hoàn toàn phù hợp. Chắc chắn một điều là phiên bản mới nhất tốt không thể tốt hơn 10 lần so với phiên bản cũ hơn, ngay cả khi đó là sự khác biệt về giá giữa hai phiên bản!

#### Ai tạo ra hướng dẫn này?

Hướng dẫn này ban đầu được viết bởi [Oz Nova](https://twitter.com/oznova_) và [Myles Byrne](https://twitter.com/quackingduck), với các cập nhật vào 2020 của Oz. Nó dựa trên kinh nghiệm của chúng tôi giảng dạy kiến thức khoa học máy tính nền tảng cho hơn 1000 kỹ sư chủ yếu là tự học và sinh viên tốt nghiệp bootcamp mà học trong các nhóm nhỏ ở San Francisco hay trực tuyến. Cảm ơn tất cả các sinh viên của chúng tôi vì đã tiếp tục phản hồi về các nguồn tài liệu tự học.

Chúng tôi rất tự tin rằng bạn có thể tự học mọi thứ ở trên, nếu có đủ thời gian và động lực. Nhưng nếu bạn thích một chương trình chuyên sâu, có cấu trúc, có người hướng dẫn, bạn có thể quan tâm đến khoá học về máy tính trên https://bradfieldcs.com/csi/ của chúng tôi. Chúng tôi [KHÔNG](https://ozwrites.com/masters/) khuyên bạn theo đuổi bằng thạc sĩ.

Để nhận các cập nhật mới về hướng dẫn này, tin tức và tài liệu về ngành khoa học máy tính, bạn có thể đăng ký email của bạn với Bradfield: [truy cập vào cuối trang https://teachyourselfcs.com/ để đăng ký].

[hello@bradfieldcs.com](mailto:hello@bradfieldcs.com). Sanfrancisco, California. © 2016-2020 Trường Khoa học Máy tính Bradfield.