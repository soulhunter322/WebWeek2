---
layout: page
title: Blog
permalink: /blog/
---

<h1><b>ReactJS Có Gì Lợi Hại Mà Lazada, Tiki, Shopee, Sendo Và Các Trang Thương Mại Điện Tử Lớn Khác Đều Đang Sử Dụng?</b></h1>

<article>
<h2>ReactJS là gì, có ăn được không?</h2>
<p>ReactJs là một thư viện được tạo ra bởi Jordan Walke, một kỹ sư làm việc tại Facebook. Ông thần này đã cho ra mắt phiên bản mẫu đầu tiên của React được gọi với cái tên mỹ miều là FaxJS, nghe lạ quá nhỉ.</p>
<p>React đã được áp dụng trên New Feed của Facebook vào năm 2011 và không lâu sau đó là trên Instagram vào năm 2012.ReactJS là một thư viện hỗ trợ xây dựng các thành phần của giao diện người dùng (UI library).</p>
<h2>Tại sao nên học ReactJS?</h2>
<p>Quay lại ngày trước thời chúng ta mới mày mò học làm web, phía front end (giao diện người dùng – UI – User Interface) chúng ta đã học HTML, CSS, Javascript và Jquery. Để tạo ra một giao diện đẹp như tầm hot girl trở lên thì phải viết code quá trời là viết, mà việc tái sử dụng lại cũng như việc tìm code để bảo trì những  hậu quả đó cũng lòi con mắt và rất chi là khó khăn.</p>
<p>Để có trải nghiệm người dùng tốt hơn (UX – User Experience) chúng ta thường hay sử dụng AJAX của thư viện Jquery để tạo ra các hiệu ứng cũng như thay đổi dữ liệu hiển thị mà không phải load lại toàn bộ trang web, điều đó thật tuyệt vời phải không. Nó giống như chức năng giỏ hàng của các trang thương mại điện tử khi chúng ta ấn thêm vào giỏ hàng thì giỏ hàng được cập nhật ngay trước mắt mà không phải load lại toàn bộ trang web hoặc thấy rõ hơn là New Feed của Facebook khi chúng ta lướt Facebook thì các tin của những người bạn được hiển thị lên một cách mượt mà mà không có dấu hiệu load lại trang như chúng ta nhấn phím F5.</p>
<p>Ok, vậy việc sử dụng Jquery để làm những điều đó vẫn được mà phải không? Đúng là vẫn được nhưng đó là một cách tự sát vì càng sinh ra nhiều chức năng thì số lượng code rối rắm tăng và khả năng bảo trì và phát triển về sau sẽ giảm. Và mình cũng  xin nói thêm là Jquery là một thư viện hỗ trợ giao diện người dùng tốt nhưng để tạo được sự rõ ràng rành mạch trong việc code một dự án lớn thì Jquery phải nhường bước cho các thư viện và framework hiện đại như Angular, VueJS, ReactJS. mình sẽ tập trung vào chủ đề chính là ReactJS nha, ở bài viết này mình sẽ chưa so sánh giữa Angular, VueJS và ReactJS.</p>
<p>Các thư viện và framework hiện đại này đem lại trải nghiệm người dùng (UX) tốt cũng như code sẽ rõ ràng và dễ bảo trì hơn là code với Jquery.</p>
<p>Tại sao code ReactJS lại đem lại trải nghiệm người dùng (UX) tốt? Bởi vì nó được sinh ra để hướng đến một khái niệm gọi là Single Page Application tức có nghĩa là việc thao tác của người dùng sẽ ở trên cùng một trang và các thao tác này thay đổi dữ liệu hiển thị nhưng không bị load lại toàn bộ trang việc này ReactJS cung cấp giải pháp khá tốt đó là quản lý việc hiển thị bằng cây DOM ảo (Virtual DOM), những thành phần giao diện sẽ được quản lý bởi cây DOM ảo này và nó sẽ thay đổi dựa vào các state (trạng thái). Khi các state (trạng thái) của các thành phần giao diện (components) thay đổi thì các thành phần giao diện trong cây DOM ảo này cũng thay đổi theo.</p>
<p>Tại sao code ReactJS lại dễ dàng bảo trì và mở rộng hơn? Bởi vì ReactJS chia một giao diện lớn thành nhiều thành phần giao diện (components) riêng biệt, và giữa các thành phần giao diện này giao tiếp với nhau thông qua props (properties) hoặc state. Khi một giao diện phức tạp được phân chia nhỏ thành các component thì sẽ dễ phát triển cũng như có thể tái sử dụng lại các component này ở một project khác hoặc một trang khác cần đến nó, như vậy thì code sẽ ngắn gọn hơn và có thể tái sử dụng được.</p>
<h2></h2>
<p>SEO được viết tắt của Search Engine Optimization.</p>
<p>Ban đầu mình học ReactJS và cũng thắc mắc câu hỏi này, ReactJS dùng để xây dựng ứng dụng Single Page Application mà vậy việc phát triển web bằng ReactJS có SEO được không? Câu trả lời là hoàn toàn được nha các bạn.</p>
<p>Single Page Application (SPA) được biết là các code phía giao diện là do client đảm nhiệm việc render, điều này giúp giảm tải lượng công việc phải làm cho Server, khi giao diện cần Server cung cấp gì để hiển thị lên thì Client sẽ gửi các yêu cầu (request) lên Server để lấy dữ liệu và hiển thị ra giao diện người dùng.</p>
<p>Nhắc tới Single Page Application thì cũng cần nhắc tới Server Side Rendering (SSR). SSR tức có nghĩa là việc render code hoàn toàn do Server phụ trách toàn bộ, nhưng SSR hiệu quả cho việc SEO hơn là SPA bởi vì bot index của Google sẽ đọc được các thông tin từ phía Server render ra như các thẻ meta data hay đường dẫn thân thiện (URL Friendly), còn những đoạn code Javascript được render từ phía client SPA, do nó không có cấu trúc cụ thể, rõ ràng thì bot Google sẽ không hiểu và không thèm đọc đến.</p>
<p>Với các doanh nghiệp làm SPA như Facebook hay Gmail của Google thì việc SEO đối với họ không quan trọng mà quan trọng là trải nghiệm người dùng(UX) với những trang bán hàng như Tiki, Lazada, Shopee, Sendo thì lại khác họ cần SEO để người dùng có thể tìm thấy sản phẩm của họ trên các công cụ tìm kiếm như Google, Bing, Yahoo điều này giúp tăng doanh thu bán hàng của họ. </p>
<p>Nhưng câu hỏi đặt ra là ReactJS hướng tới phát triển ứng dụng SPA mà sao các doanh nghiệp này vẫn dùng, làm sao họ có thể SEO sản phẩm được kia chứ? </p>
<p>Bạn cứ bình tỉnh nghe mình giải thích nhé, theo mình biết thì có 2 cách như vầy. Nếu bạn xây dựng một ứng dụng ReactJS thuần SPA luôn thì không nói, bạn sẽ viết code và toàn bộ code của bạn sẽ được đóng gói vào trong 1 file Javascript duy nhất hay gọi là file bundle.js và gắn nó vào trang của bạn. </p>
<p>Nhưng để một trang web có thể SEO được nó cần nhiều yếu tố nhưng những yếu tố hàng đầu là các thẻ meta phải được render từ phía Server, thì người ta mới nghĩ ra cách là:</p>
<p>Cách 1: thay vì sử dụng toàn bộ ứng dụng là code ReactJS thì người ta sẽ code ReactJS cho những thành phần nào quan trọng và phức tạp đòi hỏi trải nghiệm người dùng cao thì họ sẽ viết code ReactJS và sau đó build, đóng gói và cho nó hiển thị vào một phần nào đó của giao diện mà thôi, phần code còn lại thì không sử dụng ReactJS. </p>
<p>Cách 2: Sử dụng SSR cho toàn bộ ứng dụng tức có nghĩa là render code ReactJS từ phía Server luôn. Nó có một số thư viện ở một số ngôn ngữ sẽ hỗ trợ chúng ta điều này. Theo mình biết với NodeJS thì có NextJS nó giúp chúng ta viết code ReactJS thoải mái và nó sẽ phụ trách việc render code ReactJS từ phía Server, hỗ trợ SEO cực tốt giống như cách mà Tiki đang sử dụng. Nếu các bạn không tin thì các bạn có thể vào trang https://tiki.vn và nhấn Ctrl + U để xem nguồn trang.</p>
<p></p>
<p></p>
<p></p>

</article>