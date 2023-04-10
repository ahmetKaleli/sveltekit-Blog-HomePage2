
<div class="kapsayan">
   
    <div class="header">
        <ul>
            <a href="#"><li>Home Page</li></a>
            <a href="#"><li>Communication</li></a>
            <a href="#"><li>About Us</li></a>
            <a href="#"><li>Bag</li></a>
          
        </ul>
    </div>
    <div class="content">


        <div class="giris">
            <table>
                <tr>
                    <td>
                        <input type="text" placeholder="Username">
                    </td>
                </tr>
                <tr>
                    <input type="password" placeholder="Password">
                </tr>
                <tr>
                    <td>
                        <a href="#"><button>Login</button></a>
                    </td>
                </tr>
            </table>
        </div>

        <div class="kategori">
            <ul>
                <a href="#"><li>Laptop</li></a>
                <a href="#"><li>Computer</li></a>
                <a href="#"><li>Phone</li></a>
                <a href="#"><li>Tablet</li></a>
              
            </ul>
            
        </div>

        <table>
            <tr>
                <td>
                    <img src="src/img/lap.png" alt="laptop">
                </td>
                <td>
                    <img src="src/img/lap2.png" alt="laptop">
                </td>
            </tr>
            <tr>
                <td>
                    <img src="src/img/mü.png" alt="comp">
                </td>
                <td>
                    <img src="src/img/4.webp" alt="tablet">
                </td>
            </tr>
            <tr>
                <td>
                    <img src="src/img/tab2.webp" alt="tablet">
                </td>
                <td>
                    <img src="src/img/tel.png" alt="phone">
                </td>
            </tr>
            <tr>
                <td>
                    <img src="src/img/tel2.png" alt="phone">
                </td>
                <td>
                    <img src="src/img/tel3.png" alt="phone">
                </td>
            </tr>
        </table>
    </div>
</div>

<style>
    *{
        margin: 0px;
        padding: 0px;
        text-decoration: none;
        border: none;
    }

    .kapsayan{
        height: 100%;
        display: block;
        background-color: rgb(111, 148, 185);
    }

    .kapsayan .header{
        position: relative;
        height: 100px;
        background-color: rgb(86, 123, 160);
    }

    .kapsayan .header ul{
        text-align: center;
        list-style-type:none;

    }

    .kapsayan .header ul li{
        float: left;
        color: #ffffff;
        background-color: rgb(82, 150, 217);
        border-radius:40px;
        text-align:center;
        line-height:40px;
        width:170px;
        margin-left: 170px;
        margin-top: 25px;
    }
    .kapsayan .header ul li:hover{
        background-color: rgb(58, 154, 154);
        color:white
    }

    .kapsayan .content .kategori {
        position: fixed;
        width: 250px;
        height: 200px;

    }

    .kapsayan .content .kategori ul{
        margin-top: 20px;
        text-align: center;
    }
    .kapsayan .content .kategori ul li{
        margin-top: 20px;
        color: #000;
        line-height: 30px;
    }

    .kapsayan .kategori ul li:hover{
        background-color: rgb(58, 154, 154);
        color:white
    }
    .kapsayan .content {
        flex:1;
    }

    .content table{
        margin-left:auto; 
        margin-right:auto;  
        border-radius: 20px;
        padding: 33px;
        margin-top: 20px;
        background-color: rgb(86, 123, 160);
    }

    .content table img{
        width: 300px;
        height: 300px;
    }
    .content .giris{
        float: right;
        margin-right: 10px;
        position: relative;
    }

    .kapsayan .content .giris tr button {
        float: right;
    }

    .giris input{
        border-radius: 15px;
        height: 30px;
        background-color:rgb(111, 148, 185);
        margin-top: 15px;
    }

    .giris button{
        margin-top: 20px;
        height: 40px;
        width: 70px;
        border-radius: 20px;
        color: white;
        background-color: rgb(62, 201, 62);
    }

    ::placeholder {
        color: white;
        opacity: 0.7; /* Firefox */
        text-align:center;
    }
</style>