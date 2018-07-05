
## Làm thế nào để viết mô tả Meta trong một thế giới thay đổi liên tục(AKA Google Giveth, Google Taketh)



**Tóm tắt: **Vào giữa tháng 8 năm 2018, Google đã trở lại việc hiển thị đoạn trích ngắn hơn. Dữ liệu của chúng tôi cho thấy những thay đổi này phổ biến và hấu hết các mô tả Meta đang bị cắt trong phạm vi trước đó khoảng 155- 160 kí tự.

Trở lại vào tháng 12, Google đã thực hiện một thay đổi đáng kể về cách họ hiển thị đoạn trích tìm kiếm, với nghiên cứu của chúng tôi cho biết nhiều đoạn trích hơn 300 kí tự. Cuối tuần qua, họ dường như đã quay trở lại với thay đổi đó ( Danny Suliivan [đã xác nhận một phần điều này](https://twitter.com/dannysullivan/status/996065145443893249) trên Twitter vào ngày 14 tháng 5. Bên cạnh những câu hỏi hiển nhiên mà ta sẽ đặt ra rằng  - Giới hạn mới là gì? - Điều đó có thể khiến bạn tự hỏi làm thế nào để đối phó khi các quy tắc tiếp tục thay đổi. Không ai trong chúng ta có một quả cầu pha lê, nhưng tôi sẽ cố gắng trở lời cả 2 câu hỏi dựa trên những điều chúng ta mà ngày nay chúng ta đã biết.

## Lies, dirty lies, and statistics... (Lời dối trá, dối trá dơ bẩn, và các thống kê ... )

Tôi đã lấy tất cả các đoạn trích tìm kiếm có sẵn từ MozCast 10k (Trang-1 Goolge cho ra 10, 000 từ khóa), Vì đó là tập dữ liệu chúng tôi thu thập hằng ngày và có một lịch sử phong phú. Có 89,383 đoạn trích hiển thị trên dữ liệu đó vào sáng ngày 15 tháng 5.

Tôi sẽ nói với bạn điều này, trên toàn bộ tập dữ liệu, độ dài nhỏ nhất là 6 kí tự,
độ dài lớn nhất là 386 kí ự, và trung bình có khoảng 159. Điều này không thực sự hữu dụng, vì một vài lý do. Thứ nhất, yêu cầu bạn viết một mô tả Meta khoảng 6 - 386 kí tự không phải là một lời khuyên hữu ích. Thứ 2, chúng ta đang phải đối phó với nhiều trường hợp. Ví dụ, đoạn trích tìm kiếm "USMC" ở đây: 

![](//d1avok0lzls2w.cloudfront.net/uploads/blog/meta-desc-2018-1-4065.png)

Marine Corps Community Services có thể là một tổ chức tuyệt vời, nhưng tôi xin lỗi phải thông báo rằng mô tả meta của họ, thực tế là, "apple" (Google thêm đoạn đó vào mô tả, tôi nghĩ vậy). Đoạn trích tìm kiếm ở đây trên một cửa hàng "Younkers"

![](//d1avok0lzls2w.cloudfront.net/uploads/blog/meta-desc-2018-2-4999.png)

Bỏ qua một sự nhầm lẫn đa thương hiệu nghiêm trọng của họ, tôi nghĩ tất cả chúng ta có thể đồng ý rằng "BER Meta TAG1" là không tối ưu. Nếu những trường hợp dạy bạn bất cứ điều gì, nó chỉ là những điều bạn không làm được. Điều gì xảy ra với trường hợp còn lại. Đoạn trích ở đây với 386 kí tự, từ một tìm kiếm "non-compete agreement":

![](//d1avok0lzls2w.cloudfront.net/uploads/blog/meta-desc-2018-3-12620.png)

Chú ý "Jump to Exceptions" và liên kết ở đầu. Tất cả đã được thêm bởi Google, vì vậy thật khó để nói cái gì  tính vào số lượng ký tự và những gì không được tính. Một trường hợp ở đây không thêm phần bổ sung là 370 kí tự, từ một tìm kiếm "the Hunger Games books":

![](//d1avok0lzls2w.cloudfront.net/uploads/blog/meta-desc-2018-4-11379.png)

Vì vậy chúng tôi biết rằng các đoạn trích dài hơn vẫn tồn tại. Tuy nhiên, lưu ý rằng, cả 2 đoạn trích đến từ Wikipedia, đó là một ngoại lệ với rất nhiều quy tắc SEO. Những mô tả dài này chỉ có những trường hợp bên ngoài không? Nhìn vào giá trị trung bình (hoặc trong trường hợp này, thậm chí trung bình) không thực sự cho chúng ta biết điều đó.

## The big picture, part 1 (Bức tranh tổng quan, phần 1)

Đôi khi, bạn phải để cho dữ liệu tự nói với chính mình, với nhỏ nhất của "coaxing". Hãy cùng xem xét tất các các đoạn trích đã được cắt bỏ (kết thúc bằng "...") và xóa các kết quả video (chúng ta biết từ các nghiên cứ trước đây rằng các đoạn trích này ngắn hơn một chút). Điều này cho ta 42,863 đoạn trích (chỉ bằng một nửa bộ dữ liệu từ chúng tôi). Ở đây là đồ thị của các độ dài cắt-bỏ, được thu thập thành 25 ngăn kí tự (0 - 25, 26 - 50, vv.):

![](//d1avok0lzls2w.cloudfront.net/uploads/blog/meta-desc-2018-5-4779.png)

Điều này nhìn có vẻ rất khác từ dữ liệu của chúng tôi [vào tháng 12](https://moz.com/blog/how-long-should-your-meta-description-be-2018), và được phân nhóm rõ ràng từ phạm vi 150 - 175 kí tự. Chúng tôi thấy một vài đoạn trích hiển thị Google bị cắt sau phạm vị 300+, nhưng đoạn mã này bị thu hẹp bởi các đoạn lần cắt ngắn hơn.

## The big picture, part 2 (Bức tranh tổng quan, phần 2)

Rõ ràng, có rất nhiều điều xảy ra trong phạm vi 125 - 175 kí tự, vì vậy hãy phóng to và nhìn vào phần giữa của phân bố tần suất, chia thành các nhóm nhỏ hơn gồm 5 kí tự: 
![](//d1avok0lzls2w.cloudfront.net/uploads/blog/meta-desc-2018-6-4992.png)

Chúng tôi có thể thấy khá rõ ràng rằng phần lớn các phần cắt bỏ xảy ra trong phạm vi 145 - 165 kí tự. Trước tháng 12,  các hướng dẫn trước đây mô tả meta giữ chúng dưới 155 kí tự, do đó, có vẻ như google đã nhiều hoặc ít là đã quay lại các quy tắc cũ.

Hãy nhớ rằng Google sử dụng phông chữ tỉ lệ thuận, vì vậy không có giới hạn kí tự chính xác. Một số người đã đưa ra giả thuyết giới hạn một pixel-width, giống với thẻ tiêu đề, nhưng tôi thấy rằng khó khăn hơn để ghim xuống với các đoạn trích nhiều dòng (tình huống thậm chí có khó khăn trên kết quả di động). Thực tế, điều đó cũng khó để viết tới giới hạn pixel. Các dữ liệu cho thấy rằng 155 kí tự là hợp lí.

## To the Wayback Machine... ?! 

Chúng ta có nên quay trở lại việc cắt bỏ 155 kí tự? Nếu bạn thực sử đã viết một mô ta meta dài hơn, bạn có nên xóa nó và bắt đầu lại? Một sự thật đơn giản là không ai trong chúng ta biết điều gì đang xảy ra trong tuần tới. Các tôi thấy nó, chúng ta có bốn lựa chọn khả thi:

### (1) Let Google handle it ( Hãy để Google xử lý nó)

Một vài trang web không có tất cả các mô tả meta. Wikipedia là một trong số chúng. Hiện nay, sự hiểu biết của Google về nội dung của Wikipedia là tốt hơn nhiều so với hầu hết các trang web (một phần, nhờ Wikipeida), nhưng nhiều trang web làm tốt hơn mà không có thẻ. Nếu lựa chọn của bạn là viết thẻ không hợp lệ, lặp lại hoặc để trống chúng, thì tôi sẽ nói để trống chúng và hãy để Google sắp xếp lại.  

### (2) Let the ... fall where it may ( Hãy để ... rơi đúng nơi có thể )

Bạn có thể viết với độ dài mà bạn nghĩ là ý tưởng cho bất gì một trang nào (trong suy luận) và nếu các đoạn trích bị căt, đừng lo về điều đó. Có thể dấu ba chấm (...) được thêm vào sau.Tôi chỉ nửa đùa ở đây thôi , nhưng thực tế việc cắt bỏ không phải là "nụ hôn của thần chết". Một mô tả tốt có thể lôi kéo mọi người muốn đọc nó.

### (3) Chop everything at 155 characters (Cắt tất cả ở 155 kí tự)

Bạn có thể trở lại và hack tất cả công việc khó khăn của bạn trở lại 155 kí tự. Tôi nghĩ điều đó là thường sẽ mất nhiều thời gian và có thể dẫn đến các đoạn trích có kết quả tìm kiếm thậm chí tệ hơn. Nếu bạn muốn viết lại mô tả Meta ngắn hơn cho các trang quan trọng của bạn, điều đó là hoàn toàn hợp lý, nhưng hãy nhớ rằng, có một vài kết quả vẫn hiển trị đoạn trích dài và tình trạng sẽ tiếp tục tăng lên.

### (4) Write length-adaptive descriptions ( Viết mô tả độ dài-thích ứng)

Có thể viết mô tả hoạt động tốt ở cả hai độ dài không? Tôi nghĩ rằng có thể, với một vài sự quan tâm và lập kế hoạch. Tôi sẽ không nhất thiết đề xuất điều này cho mọi trang đơn lẻ, nhưng có lẽ có cách ăn bánh và ăn ít nhât một nửa của nó,...

## The 150/150 approach (Cách tiếp cận 150/150)

Tôi đã bị ám ảnh một chút với "[Kiểu kim tự tháp ngược](https://moz.com/blog/content-for-answers-inverted-pyramid)" phong cách viết gần gây. Đây là phong cách báo chí nơi bạn bắt đầu với sự dẫn đầu hoặc tóm tắt điểm chính của bạn sau đó chi nhỏ chi tiết, dữ liệu và ngữ cảnh. Mặc dù các tiếp cận này phù hợp tốt với trang web, nguồn gốc của nó xuất phát từ giới hạn bố cục của bản in. Bạn không bao giờ biết khi nào bộ soạn thảo của bạn sẽ phải cắt ngắn bài viết của bạn vừa với không gian sẵn có. Do đó, phong cách "kim tự tháp ngược" đảm bảo rằng phần quan trọng nhất thường được bỏ qua.
Điều gì xảy ra nếu chúng tôi thực hiện phương pháp này để mô tả meta? Nói cách khác, tại sao không viết 150 kí tự "dẫn đầu" tóm tắ trang, và sau đó thêm 150 kí tự  hữu tích nhưng ít cần thiết hơn (Khi thêm, chi tiết đó có ý nghĩa và giá trị)? 150/150 không phải là  số ma thuật - bạn có thể  làm 100/100 hoặc 100/200. Điều quan trọng là đảm bảo rằng văn bản trước khi cắt có thể tự đứng vững.

Suy nghĩ một chút giống như quảng cáo, với 2 dòng riêng biệt  của bản sao. Hãy lấy bài đăng trên blog này:

### Line 1 (145 chars.) (Dòng 1 145 kí tự)

Vào tháng 12, chúng tôi đã thông báo rằng Google đã đoạn trích tìm kiếm lên hơn 300 kí tự. Thật không may, có vẻ như các quy tắc đã thay đổi lần nữa.

### Line 2 (122 chars.) (Dòng 2 122 kí tự)

Nghiên cứu mới nhất của chúng tôi (tháng 5 năm 2018), giới hạn đã trở lại 155-160 kí tự. Làm thế nào SEO có thể thích ứng với những thay đổi này?

Dòng 1 có phiên bản ngắn của câu chuyện và hy vọng người tìm kiếm biết rằng họ đang đi đúng hướng. Dòng 2 đi sâu vào một vài chi tiết và cho đi đủ dữ liệu (hy vọng) là hấp dẫn. Nếu Google sử dụng đủ dài mô tả, nó sẽ hoạt động tốt, nhưng nếu không, chúng ta không nên tệ hơn khi mặc.

## Should you even bother? (Bạn có nên bận tâm không)

Đây có phải là nỗ lực đáng giá không? Tôi nghĩ rằng việc viết các mô tả hiệu quả thu hút khách truy cập tìm kiếm vẫn rất quan trọng, theo lý thuyết (và điều này ảnh hưởng gián tiếp đến cả xếp hạng), nhưng bạn có thể thấy bạn có thể viết hoàn toàn tốt trong giới hạn 155 ký tự. Chúng ta cũng phải đối mặt với thực tế rằng Google dường như đang viết lại các mô tả ngày càng nhiều. Điều này rất khó để đo lường, vì nhiều lần viết lại là một phần, nhưng không đảm bảo rằng meta description của bạn sẽ được sử dụng như được viết.

Có cách nào để biết khi nào một đoạn trích dài hơn (>300 ký tự) vẫn sẽ được sử dụng? Một số SEO đã đưa ra giả thuyết một liên kết giữa các đoạn mã dài hơn và các đoạn trích nổi bật ở đầu trang. Trong tập dữ liệu tổng thể của chúng tôi, 13,3% trong tổng số SERP có đoạn trích nổi bật. Nếu chúng ta chỉ xem SERP có độ dài đoạn trích hiển thị tối đa là 160 ký tự (nghĩa là không có kết quả nào dài hơn 160 ký tự), thì đoạn mã nổi bật xuất hiện là 11,4%. Nếu chúng ta xem SERP với ít nhất một đoạn trích hiển thị trên 300 ký tự, các đoạn trích nổi bật xảy ra với tỷ lệ 41,8%. Trong khi tập dữ liệu thứ hai là khá nhỏ, nó là một sự khác biệt nổi bật. Dường như có một số kết nối giữa khả năng trích xuất câu trả lời của tôi dưới dạng đoạn trích nổi bật và khả năng hoặc sự sẵn sàng của họ để hiển thị các đoạn trích tìm kiếm dài hơn. Tuy nhiên, trong nhiều trường hợp, các đoạn trích dài hơn này được viết lại hoặc được lấy trực tiếp từ trang, vì vậy ngay cả khi đó, không có gì đảm bảo rằng Google sẽ sử dụng mô meta dài hơn của bạn.

Hiện tại, có vẻ như hướng dẫn với 155 ký tự được quay trở lại. Nếu bạn đã tăng một số meta desciption của bạn, tôi không nghĩ có lý do gì để hoảng loạn. Nó có thể có ý nghĩa để viết lại các mô tả quá dài trên các trang quan trọng, đặc biệt nếu các phần cắt giảm dẫn đến kết quả xấu. Nếu bạn chọn viết lại một số trong số chúng, hãy xem xét cách tiếp cận 150/150 - ít nhất thì bạn sẽ được kiểm chứng một chút trong tương lai.
