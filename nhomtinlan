<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ẩm Thực Việt Nam</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
        }

        header {
            background-color: #ff6f61;
            color: white;
            text-align: center;
            padding: 2rem;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        nav {
            background-image: url('https://res.klook.com/image/upload/q_85/c_fill,w_750/v1711537582/ttvzkybg1v5gk8bxktsp.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        nav ul li {
            padding: 1rem;
            position: relative; /* Để con menu hiển thị đúng */
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            text-transform: uppercase;
        }

        /* Menu con */
        nav ul li ul {
            list-style: none;
            position: absolute;
            top: 100%;
            left: 0;
            background-color: #333;
            display: none;
            min-width: 200px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        nav ul li:hover > ul {
            display: block;
        }

        nav ul li ul li {
            padding: 0.5rem 1rem;
        }

        nav ul li ul li a {
            color: white;
            text-decoration: none;
            display: block;
        }

        section {
            padding: 3rem 2rem;
            max-width: 1200px;
            margin: auto;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            display: none;
        }

        .region {
            display: none;
        }

        .active {
            display: block;
        }

        .region h2 {
            color: #ff6f61;
            text-align: center;
            font-size: 2rem;
            margin-bottom: 1rem;
            text-transform: uppercase;
            font-weight: bold;
        }

        .province {
            margin-top: 1.5rem;
        }

        .province h3 {
            color: #ff6f61;
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }

        .province ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .province ul li {
            margin-bottom: 1.5rem;
            font-size: 1.1rem;
        }

        .province ul li strong {
            color: #333;
        }

        .province img {
            max-width: 100%;
            border-radius: 8px;
            margin-top: 1rem;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1.5rem;
            position: relative;
            margin-top: 3rem;
        }

        .footer-link {
            color: #ff6f61;
            text-decoration: none;
            font-weight: bold;
        }

        .led {
            font-size: 1.5rem;
            color: red;
            white-space: nowrap;
            overflow: hidden;
            position: relative;
            background: black;
            padding: 10px 0;
            width: 100%;
        }

        .led span {
            display: inline-block;
            animation: marquee 10s linear infinite;
        }

        @keyframes marquee {
            from {
                transform: translateX(100%);
            }
            to {
                transform: translateX(-100%);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Khám Phá Ẩm Thực Việt Nam</h1>
        <p>Khám phá các món ăn đặc sắc từ ba miền Bắc, Trung, Nam.</p>
    </header>

    <!-- Dòng chữ LED chào mừng -->
    <div class="led">
        <span>Chào mừng các bạn đến với trang giới thiệu món ăn của Hoàng Lân, Phương Du, Đức Hà, Tuệ Minh</span>
    </div>

    <!-- Thanh công cụ -->
    <nav>
        <ul>
            <li><a href="javascript:void(0);" onclick="showRegion('trang-chu')">Trang Chủ</a></li>
            <li>
                <a href="javascript:void(0);" onclick="showRegion('mien-bac')">Miền Bắc</a>
                <ul>
                    <li><a href="javascript:void(0);" onclick="showRegion('mien-bac')">Hà Nội</a></li>
                    <li><a href="javascript:void(0);" onclick="showRegion('mien-bac')">Hưng Yên</a></li>
                    <li><a href="javascript:void(0);" onclick="showRegion('mien-bac')">Hải Phòng</a></li>
                     </ul>
            </li>
            <li>
                <a href="javascript:void(0);" onclick="showRegion('mien-trung')">Miền Trung</a>
                <ul>
                    <li><a href="javascript:void(0);" onclick="showRegion('mien-trung')">Huế</a></li>
                    <li><a href="javascript:void(0);" onclick="showRegion('mien-trung')">Đà Nẵng</a></li>
                    <li><a href="javascript:void(0);" onclick="showRegion('mien-trung')">Quảng Ngãi</a></li>
                </ul>
            </li>
            <li>
                <a href="javascript:void(0);" onclick="showRegion('mien-nam')">Miền Nam</a>
                <ul>
                    <li><a href="javascript:void(0);" onclick="showRegion('mien-nam')">TP HCM</a></li>
                    <li><a href="javascript:void(0);" onclick="showRegion('mien-nam')">Cà Mau</a></li>
                    <li><a href="javascript:void(0);" onclick="showRegion('mien-nam')">Cần Thơ</a></li>
                </ul>
            </li>
            <li><a href="javascript:void(0);" onclick="showRegion('ve-chung-toi')">Về Chúng Tôi</a></li>
        </ul>
    </nav>

    <!-- Phần giới thiệu chung (Trang chủ) -->
    <section id="trang-chu" class="region active">
        <h2>Giới Thiệu Chung</h2>
        <p><strong>Miền Bắc:</strong> Miền Bắc có khí hậu ôn đới, 4 mùa rõ rệt. Nét đặc trưng phải kể đến trong ẩm thực miền Bắc chính là sự hài hòa trong cảm quan, hương vị rất vừa phải, không quá chua, quá cay, quá mặn hay quá nồng. Ẩm thực miền Bắc đề cao sự thanh tao, đạm bạc nhưng vẫn tôn lên được những hương vị tinh túy của những món ăn.  Nơi đây nổi tiếng với những món ăn đặc trưng như Phở, Bún Chả, và Bánh Cuốn.</p>
       <!-- Thêm video -->
        <h3>Video về ẩm thực miền Bắc</h3>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/q_JF97fMw3o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
        <p><strong>Miền Trung:</strong> Miền Trung có khí hậu nhiệt đới gió mùa, nắng nóng quanh năm. Ẩm thực miền Trung là một tổng thể cân đối, hài hòa và tinh tế. Các món ăn miền Trung hầu hết đều mang hương vị đặc trưng là cay và mặn. Họ cũng thích vị ngọt nhưng ở mức độ vừa phải. Nói theo cách khác, món ăn dù có đơn giản thì cũng phải đậm đà, bởi theo quan niệm của người miền Trung món ăn phải đậm đà thì mới ngon. Món ăn nổi tiếng là Cơm hến, Bánh Canh.</p><!-- Thêm video -->
        <h3>Video về ẩm thực miền Trung</h3>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/aRBlQgQKDp0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
        <p><strong>Miền Nam:</strong> Miền Nam có khí hậu nóng ẩm quanh năm.Tùy vào mùa nước nổi hay mùa gặt, “thực khách” sẽ được thưởng thức những món ăn dân dã. Từ những nguyên liệu đặc trưng của mùa như lẩu cá linh điên điển, bún nước lèo, bông súng kho mắm; những loại cá đồng béo ngậy hay những loại rau, bông, đọt cây được chế biến theo nhiều cách đa dạng khác nhau.… Các món ăn đặc trưng của miền Nam là Hủ Tiếu, Bánh Mì, và Lẩu Mắm.</p><!-- Thêm video -->
        <h3>Video về ẩm thực miền Nam</h3>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/RKgY7zyZYrA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</section>
    

    <!-- Phần nội dung các miền -->
    <section id="mien-bac" class="region">
        <h2>Ẩm Thực Miền Bắc</h2>
        <div class="province">
            <h3>Hà Nội</h3>
            <ul>
                <li><strong>Phở:</strong> Phở Hà Nội là một món ăn truyền thống nổi tiếng của Việt Nam, đặc biệt là ở thủ đô Hà Nội. Đây là một dạng phở có nước dùng trong, thanh, và thường được làm từ xương bò hoặc xương gà ninh nhừ để tạo ra vị ngọt tự nhiên.
 <img src="https://static.vinwonders.com/production/pho-bo-ha-noi.jpeg" alt="Phở Hà Nội"></li>
                <h3>Hưng Yên</h3>
            <ul>
                <li><strong>Ếch om Phượng Tường Hưng Yên
:</strong> Một đặc sản Hưng Yên không thể không thử một lần trong đời là món ếch om Phượng Tường. Chỉ cần nghe đến tên gọi thôi, ếch om Phượng Tường cũng đủ làm xao xuyến bao thực khách. Món ăn có nguồn gốc từ làng Phượng Tường, huyện Tiên Lữ, Hưng Yên.
 <img src="https://ik.imagekit.io/tvlk/blog/2022/09/dac-san-hung-yen-5-1024x683.jpg?tr=q-70,w-625,dpr-2" alt="Ếch om Phượng Tường Hưng Yên"></li>
 <h3>Hải Phòng </h3>
            <ul>
                <li><strong>Bánh Mì Que Hải Phòng
:</strong> Bên trong chiếc bánh là nhân pate đơn giản nhưng lại đậm đà và ngon miệng. Sự kết hợp hài hòa giữa vỏ bánh mì giòn tan và nhân pate thơm ngon tạo nên một trải nghiệm ẩm thực độc đáo.
Điều đặc biệt là bánh mì cay không chỉ đảm bảo tiêu chí "ngon, bổ, rẻ" mà còn mang đến hương vị đúng chất. Dù có thể tìm thấy bánh mì cay ở nhiều nơi, nhưng hương vị thật sự tuyệt vời nhất vẫn nằm ở Hải Phòng - đất cảng nổi tiếng. Vậy nên, khi đến thăm thành phố này, đừng bỏ qua cơ hội thưởng thức món ăn thú vị này..
 <img src="https://res.klook.com/image/upload/fl_lossy.progressive,q_85/c_fill,w_1000/v1687103546/ojr8ksdedwuqw49pxujk.webp" alt="Bánh mì que Hải Phòng"></li>
            </ul>
        </div>
    </section>

    <section id="mien-trung" class="region">
        <h2>Ẩm Thực Miền Trung</h2>
        <div class="province">
            <h3>Huế</h3>
            <ul>
                <li><strong>Cơm hến Huế :</strong> Đến Huế, bạn sẽ không khó để bắt gặp một quán cơm hến ở mọi ngóc ngách thành phố. Cơm hến phổ biến ở Huế như đặc sản phở ở Hà Nội vậy. Thành phần chính của món cơm này gồm cơm nấu chín để nguội, hến xào thơm ăn cùng tóp mỡ, mắm ruốc thêm một số gia vị và rau sống như rau thơm, bắp chuối, giá đỗ, … Vị hến xào càng ngon thì món đặc sản của Huế này càng trở nên hấp dẫn. Bởi vậy, bạn nên chọn được quán có công thức làm hến ngon thì mới cảm nhận được tinh hoa của món ăn. <img src="https://cdn.hoabinhevents.com/hbt/wp-content/uploads/2024/05/21142113/dac-san-hue-hbt2.jpg" alt="Cơm hến Huế"></li>
                <h3>Đà Năng</h3>
            <ul>
                <li><strong>Bánh canh ruộng :</strong>Đừng để cái tên giản dị đánh lừa bạn, bánh canh ruộng Đà Nẵng là một món ăn bình dân nhưng lại có sức hút khó cưỡng, khiến không ít du khách phải "xiêu lòng".
Tô bánh canh nóng hổi, thơm lừng với sợi bánh dày, dai, được làm từ bột gạo, hòa quyện cùng nước dùng ngọt thanh từ xương heo, tạo nên một hương vị đậm đà, khó quên. Bánh canh ruộng Đà Nẵng đa dạng với nhiều loại topping hấp dẫn, từ cá lóc đồng tươi ngon, chả cá dai ngọt đến cua gạch béo ngậy, hay đơn giản nhưng vẫn đủ sức "gây thương nhớ" là bánh canh trứng cút.
. <img src="https://res.klook.com/image/upload/fl_lossy.progressive,q_85/c_fill,w_1000/v1686984438/mpvytsyy3kgerlxx8fsi.webp
" alt="Bánh canh ruộng"></li><h3>Quảng Ngãi</h3>
            <ul>
                <li><strong>Bánh xèo:</strong> Nếu bạn còn đang thắc mắc đặc sản Quảng Ngãi là gì thì câu trả lời chắc chắn phải là bánh xèo. Khác với bánh xèo miền Bắc hay miền Tây, bánh xèo Quảng Ngãi nhỏ hơn, mỏng hơn và được đúc giòn hoặc mềm tùy theo yêu cầu của thực khách. <img src="https://static.vinwonders.com/production/dac-san-quang-ngai-3.jpg
" alt="Bánh xèo "></li>
            </ul>
        </div>
    </section>

    <section id="mien-nam" class="region">
        <h2>Ẩm Thực Miền Nam</h2>
        <div class="province">
            <h3>Thành phố Hồ Chí Minh</h3>
            <ul>
                <li><strong>Phá lẩu Sài Gòn:</strong> Phá lấu được làm từ lòng bò, lòng heo, dạ dày, lá sách và các thành phần khác. Để mang đến hương vị thơm ngon, phá lấu được nấu với nước dừa và các loại gia vị, cùng với các thảo dược. Hiện nay, không chỉ có heo, món phá lấu còn được nấu với thịt bò, thịt vịt, mực,… để mang đến sự đa dạng và phong phú cho món ăn này. <img src="https://r2.nucuoimekong.com/wp-content/uploads/pha-lau-sai-gon.jpg" alt="Phá lẩu"></li>
            <h3>Cà Mau </h3>
            <ul>
                <li><strong>Bánh tằm :</strong>Cà Mau, vùng đất cuối cùng ở phía nam đất nước, nổi tiếng với món bánh tầm hấp dẫn. Với hương vị thơm ngon, món ngon miền Nam này thu hút được lòng của nhiều du khách khi ghé thăm. Bánh tầm, còn được gọi là bánh tằm, có tên gọi đó vì sợi bánh được làm từ bột gạo. Và có hình dạng giống như những con tằm.  <img src="https://r2.nucuoimekong.com/wp-content/uploads/banh-tam-ca-mau.jpg" alt="Bánh tằm"></li>
            <h3>Cần Thơ </h3>
            <ul>
                <li><strong>Cá lóc nướng trụi:</strong> Cá lóc nướng trui được làm từ cá lóc đồng và được nướng bằng rơm. Thịt cá lóc chín mềm tạo nên một hương thơm tuyệt vời. Sau khi cá lóc chín, thịt được xẻ và trên đó được thêm mỡ hành và đậu phộng rang. <img src="https://r2.nucuoimekong.com/wp-content/uploads/ca-loc-nuong-trui-3.jpg" alt="Cá lóc nướng trụi"></li>
            </ul>
        </div>
    </section>
    <section id="ve-chung-toi" class="region">
        <h2>Về Chúng Tôi</h2>
         <p>Chúng tôi là 4 thành viên 12a8. Chúng tôi sẽ giới thiệu cho các bạn về ẩm thực Việt Nam.</p>

    <div style="border: 2px solid yellow; padding: 20px; background-color: #f9f9f9; border-radius: 8px; margin-top: 20px;">
        <h3>Liên Hệ</h3>
        <p>Vui lòng điền thông tin và phản hồi của bạn vào form dưới đây:</p>

        <!-- Form liên hệ -->
        <form action="https://formspree.io/f/maybwnyo" method="POST" style="display: flex; flex-direction: column; max-width: 400px; margin: 0 auto;">
            <label for="name">Họ và Tên:</label>
            <input type="text" id="name" name="name" required placeholder="Nhập họ tên của bạn" style="padding: 10px; margin-bottom: 10px; border: 1px solid #ccc; border-radius: 4px;">

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required placeholder="Nhập email của bạn" style="padding: 10px; margin-bottom: 10px; border: 1px solid #ccc; border-radius: 4px;">

            <label for="message">Phản Hồi:</label>
            <textarea id="message" name="message" required placeholder="Nhập phản hồi của bạn" style="padding: 10px; margin-bottom: 10px; border: 1px solid #ccc; border-radius: 4px;"></textarea>

            <button type="submit" style="background-color: #ff6f61; color: white; padding: 10px; border: none; border-radius: 4px; cursor: pointer;">Gửi</button>
        </form>
    </div>
</section>
<footer>
        <p>Mọi thông tin liên hệ qua zalo:0915654312 | <a href="#ve-chung-toi" class="footer-link">Về Chúng Tôi</a></p>
    </footer>

    <script>
        function showRegion(region) {
            // Ẩn tất cả các mục nội dung
            var sections = document.querySelectorAll('.region');
            sections.forEach(function(section) {
                section.classList.remove('active');
            });

            // Hiển thị nội dung của miền đã chọn
            var activeRegion = document.getElementById(region);
            activeRegion.classList.add('active');
        }
    </script>
</body>
</html>

