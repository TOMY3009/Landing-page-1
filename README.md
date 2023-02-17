<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <Style>
        body{
            padding-left: 12%;
            padding-right: 12%;
            background-color: rgb(247, 246, 245);

        }
        header{
            background-color: antiquewhite;
        }
        header table{
            Width: 100%;
           text-align: right;
        }
        header a{
            text-decoration: none;
            margin: 20px;
            color:orangered;
            font-size: 20px;
        }
        section{
            background-color: rgb(195, 245, 166);
        }
        section table{
            width: 100%;
            text-align: center;
        }
        article{
            background-color: white;
            text-align: left;       
            padding-top: 30px;
        }
        Article table{
            width: 100%;
            text-align: center;
        }
        article img{
            border-radius: 15px; /Bo góc hình*/

        }
        article b{
            background-color: orange;
            color:white;
            padding: 10px;
            border-radius: 0px 15px 15px 0px;
        }
        nav{
            background-color:antiquewhite ;
            text-align: center;
            line-height: 60px;
        }
        nav input{
            height: 30px;
            width: 300px;
        }
        nav button{
            height: 35px;
        }
        aside{
            background-color: white;
            text-align: center;
            padding: 20px;
        }
        aside table{
            padding-top: 20px;
            width: 100%;
            text-align: center;
        }
        aside img{
            border-radius: 50%;
            text-align: center;
            padding: 10px;
        }
        aside b{
            background-color: orange;
            color:white;
            padding: 10px;
            border-radius: 10px;
        }
        Footer{
            background-color: antiquewhite;
            text-align: center;
            padding: 50px;
        }


    </Style>
</head>
<body>
    <header>
        <table>
            <tr>
                <td><img width="100px" src="LandingPage copy/logo.png" alt=""></td>
                <td>
                    <a href="#trangchu">Trang chủ</a>
                    <a href="#sanpham">Sản phẩm</a>
                    <a href="#chungnhan">Chứng nhận</a>
                    <a href="#phanhoi">Phản hồi</a>
                    <a href="#lienhe">Liên hệ</a>
                </td>
            </tr>
        </table>
        <img width="100%" src="LandingPage copy/banner.png">
    </header>
    <section>
        <table>
            <tr>
                <td><img width="200px" src="LandingPage copy/sonmoi1.jpeg" alt=""></td>
                <td><img width="200x" src="LandingPage copy/sonmoi2.webp" alt=""></td>
                <td><img width="200px" src="LandingPage copy/sonmoi3.webp" alt=""></td>
                <td><img width="200px" src="LandingPage copy/sonmoi4.jpeg" alt=""></td>
            </tr>
            <tr>
                <td><h3>son môi màu hồng</h3></td>
                <td><h3>son môi màu cam</h3></td>
                <td><h3>son môi màu đỏ</h3></td>
                <td><h3>Son môi màu chì</h3></td>
            </tr>
            <tr>
                <td><Button>mua ngay</Button></td>
                <td><Button>mua ngay</Button></td>
                <td><Button>mua ngay</Button></td>
                <td><Button>mua ngay</Button></td>
             </tr>
        </table> 
    </section>
    <article>
        <b id="chungnhan">CHỨNG NHẬN CHẤT LƯỢNG</b>
        <table>
            <tr>
                <td><h3>THƯƠNG HIỆU ĐẠT TOP 10 VIỆT NAM</h3></td>
                <td><img width="400px" src="LandingPage copy/thuonghieu10.png" alt=""></td>
            </tr>
            <tr>
                <td><img width="400px" src="LandingPage copy/giaithuong100.jpeg" alt=""></td>
                <td><h3>ĐẠT HUY CHƯƠNG LAO ĐỘNG</h3></td>
            </tr>
        </table>
    </article>
    <nav>
        <input type="text">
        <button>NHẬP EMAIL ĐỂ NHẬN MÃ GIẢM GIÁ</button>
    </nav>
    <aside>
        <b>PHẢN HỒI CỦA KHÁCH HÀNG </b>
        <Table>
            <tr>
                <td><img width="300px" src="LandingPage copy/tranthanh.jpeg"/td>
                <td><img width="300px" src="LandingPage copy/thuytien.jpeg"/td>
                <td><img width="300px" src="LandingPage copy/denvau.jpeg"/td>
            </tr>
            <tr>
                <td><i>Trấn Thành"Vợ khen son tuyệt vời"</i></td>
                <td><i>Thủy Tiên:"Có cả 1 bộ sưu tập rồi"</i></td>
                <td><i>Đen Vâu:"Mua tặng cho Fan 100 thỏi"</i></td>
            </tr>
        </Table>
    </aside>
    <footer>
        <b>CÔNG TY CỔ PHẦN SON ĐẸP NHẤT NGÂN HÀ</b>
        <br>
        <br>
        <b>Địa chỉ: Trần Duy Hưng, Đường số 256</b>
        <br>
        <br>
        <b>Sdt: 19001212xxx - email: sale@sondep.com</b>
    </footer>
</body>
</html>
