<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School_solved</title>
    <!-- icon_link -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
        integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <!-- Font Family Link --> 
    <link href='https://fonts.googleapis.com/css?family=Montserrat' rel='stylesheet'>

    <style>
        /* Schhol website CSS File */
body {
    position: relative;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.main {
    margin: 0 auto;
}

/* Navbar */
ul {
    position: absolute;
    list-style-type: none;
    display: flex;
    margin: 0;
    left: 55px;
}

/* Home_Head */
li.home1 {
    position: absolute;
    margin: 0 0;
    top: 33px;
    bottom: 38px;
    left: 423px;
    right: 974px;
}

li.home2 {
    font-family: 'Montserrat';
    position: absolute;
    top: 0;
    left: 83px;
    bottom: 38px;
    right: 0;
}

/* Product_head */
li.product1 {
    position: absolute;
    margin: 0 0;
    top: 33px;
    bottom: 38px;
    left: 487px;
    right: 894px;
}

li.product2 {
    position: absolute;
    top: 0;
    left: 21px;
    bottom: 38px;
    right: 0;
}

/* Pricing_head */
li.pricing1 {
    position: absolute;
    margin: 0 0;
    top: 33px;
    bottom: 38px;
    left: 567px;
    right: 821px;
}

li.pricing2 {
    position: absolute;
    top: 0;
    left: 21px;
    bottom: 38px;
    right: 0;
}

/* Contact_head */
li.contact1 {
    position: absolute;
    margin: 0 0;
    top: 33px;
    bottom: 38px;
    left: 640px;
    right: 742px;
}

li.contact2 {
    position: absolute;
    top: 0;
    left: 21px;
    bottom: 38px;
    right: 742px;
}

li a {
    position: absolute;
    font-family: 'Montserrat';
    text-decoration: none;
    font-size: 15px;
    color: #737373;
}

li a:hover {
    border-bottom: 3px solid rgb(84, 78, 78);
    color: #252B42;
}

.head {
    font-family: 'Montserrat';
    width: 186px;
    height: 32px;
    font-weight: 700;
    position: absolute;
    font-size: 30px;
    top: 22px;
    left: 130px;
    bottom: 33px;
    margin: 0 0;
    color: #252B42;
}

.container {
    margin: 0 0;
}

/* 1st part */
.rect {
    position: absolute;
    width: 703px;
    height: 543.79px;
    right: 0px;
    top: 0px;
    left: 816px;
}

.rect_1 {
    position: relative;
    width: 1220px;
    height: 710px;
    top: 80Px;
    left: 0px;
    right: 220px;
    bottom: 325px;
    z-index: -1;
}

/* Login Button */
.but1 {
    position: absolute;
    font-family: 'Montserrat';
    width: 41px;
    height: 22px;
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 22px;
    background-color: transparent;
    border: none;
    letter-spacing: 0.2px;
    top: 34px;
    left: 1017px;
    right: 461px;
    bottom: 487.79px;
    padding: 0;
    color: #96BB7C;
    cursor: pointer;
}

.but1:hover {
    color: #7f9f69;
}

/* Join us button */
.but2 {
    display: flex;
    font-family: 'Montserrat';
    align-items: center;
    padding: 15px 25px;
    gap: 15px;
    position: absolute;
    width: 137px;
    height: 52px;
    left: 1103px;
    border: none;
    top: 19px;
    right: 279px;
    background: #96BB7C;
    color: #ffffff;
    border-radius: 5px;
    cursor: pointer;
}

.but2:hover {
    background-color: #7f9f69;
}

.but2:active {
    color: #eff8ed;
    background-color: #728d5fc0;
}

/* Girl Mai_image */
.main_image {
    position: absolute;
    left: 812.13px;
    right: 80px;
    top: 70px;
    bottom: 235px;

}

.left_part {
    position: absolute;
    top: 0px;
    left: -6px;
}

/* Home Page Information */

.info1 {
    position: absolute;
    font-family: 'Montserrat';
    height: 24px;
    width: 125px;
    font-style: normal;
    font-weight: 700;
    font-size: 17px;
    line-height: 24px;
    letter-spacing: 0.1px;
    color: #96BB7C;
    margin: 0 0;
    top: 184px;
    left: 197px;
    right: 1121px;
    bottom: 829px;
}

.info2 {
    position: absolute;
    font-family: 'Montserrat';
    width: 542px;
    height: 160px;
    font-style: normal;
    font-weight: 700;
    font-size: 58px;
    line-height: 80px;
    letter-spacing: 0.2px;
    color: #252B42;
    margin: 0 0;
    top: 243px;
    left: 197px;
    right: 481px;
    bottom: 634px;
}

.info3 {
    position: absolute;
    font-family: 'Montserrat';
    width: 450px;
    height: 60px;
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 0.2px;
    color: #737373;
    margin: 0 0;
    flex-grow: 0;
    top: 438px;
    left: 197px;
    bottom: 214px;
}

.but_get_quote {
    position: absolute;
    font-family: 'Montserrat';
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 18px 40px;
    gap: 10px;
    width: 184px;
    height: 52px;
    background: #96BB7C;
    color: #ffffff;
    border-radius: 5px;
    flex: none;
    border: none;
    top: 533px;
    left: 197px;
    right: 830px;
    bottom: 127px;
    cursor: pointer;
}

.but_get_quote:hover {
    background-color: #7f9f69;
}

.but_get_quote:active {
    color: #eff8ed;
    background-color: #728d5fc0;
}

.but_learn_more {
    position: absolute;
    font-family: 'Montserrat';
    padding: 15px 40px;
    gap: 10px;
    width: 165px;
    height: 52px;
    border: 1px solid #96BB7C;
    background-color: transparent;
    color: #96BB7C;
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 22px;
    letter-spacing: 0.2px;
    border-radius: 5px;
    margin: 0 0;
    top: 533px;
    left: 400px;
    right: 658px;
    bottom: 127px;
    cursor: pointer;
}

.but_learn_more:hover {
    background-color: #7f9f6918;
}

.but_learn_more:active {
    background-color: #728d5f33;
}

/* Home_page card */
.card_main_div {
    position: absolute;
    top: 3px;
    left: 52px;
}

.card1 {
    position: absolute;
    width: 320px;
    height: 290px;
    background: #FFFFFF;
    box-shadow: 1px 1px 5px 0px rgba(0, 0, 0, 0.556);
    flex: none;
    top: 665px;
    left: 147px;
    right: 915px;
    bottom: 76px;
}

/* 1st_card */
.card1_image {
    position: absolute;
    top: 35px;
    left: 40px;
    right: 216px;
    bottom: 189px;
}

.card_info1 {
    position: absolute;
    width: 243px;
    height: 32px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 700;
    font-size: 24px;
    line-height: 32px;
    letter-spacing: 0.1px;
    color: #252B42;
    flex: none;
    margin: 0 0;
    top: 127px;
    left: 40px;
    right: 75px;
    bottom: 137px;
}

.line {
    position: absolute;
    width: 50px;
    height: 2px;
    background: #E74040;
    top: 179px;
    left: 40px;
    right: 238px;
    bottom: 115px;
}

.card_paragraph {
    position: absolute;
    font-family: 'Montserrat';
    width: 222px;
    height: 60px;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    letter-spacing: 0.2px;
    margin: 0 0;
    padding: 0 0;
    color: #737373;
    flex: none;
    top: 201px;
    left: 40px;
    right: 66px;
    bottom: 35px;
}

/* 2nd_card */
.card2 {
    position: absolute;
    width: 320px;
    height: 290px;
    background: #FFFFFF;
    box-shadow: 1px 1px 5px 0px rgba(0, 0, 0, 0.556);
    top: 665px;
    left: 555px;
    right: 557px;
    bottom: 76px;
}

/* 3rd_card */
.card3 {
    position: absolute;
    gap: 20px;
    width: 320px;
    height: 290px;
    background: #FFFFFF;
    box-shadow: 1px 1px 5px 0px rgba(0, 0, 0, 0.556);
    top: 665px;
    left: 954px;
    right: 198px;
    bottom: 76px;
}

/* Thumbail_part */
.thumbail_main {
    width: 1440px;
    height: 805px;
    background: #FFFFFF;
}

.thumbail {
    position: absolute;
    width: 521px;
    height: 474px;
    top: 1100px;
    left: 223.5px;
    right: 171px;
    bottom: 721.5px;
}

.line2 {
    width: 94px;
    height: 7px;
    background: #E74040;
    position: absolute;
    top: 1189px;
    left: 919.5px;
    right: 484.5px;
    bottom: 549px;
}

/* Thumbail_heading */
.thumbail_head {
    position: absolute;
    font-family: 'Montserrat';
    width: 252px;
    height: 100px;
    font-weight: 700;
    font-size: 40px;
    line-height: 50px;
    letter-spacing: 0.2px;
    color: #252B42;
    margin: 0;
    top: 1230px;
    left: 919.5px;
    right: 326.5px;
    bottom: 414px;
}

.thumbail_paragraph {
    position: absolute;
    font-family: 'Montserrat';
    width: 368px;
    height: 60px;
    font-weight: 400;
    font-size: 15px;
    line-height: 20px;
    letter-spacing: 0.2px;
    color: #737373;
    margin: 0;
    top: 1365px;
    left: 919.5px;
    right: 326.5px;
}

.thumbail_lern_more {
    position: absolute;
    font-family: 'Montserrat';
    width: 95px;
    margin: 0;
    height: 24px;
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #96BB7C;
    top: 1455px;
    left: 919.5px;
    right: 326.5px;
    cursor: pointer;
}

.thumbail_lern_more:hover {
    color: #7f9f69;
}

/* vedio_part */
.vedio_main {
    position: relative;
    top: 40px;
}

.vedio_img {
    position: absolute;
    gap: 30px;
    width: 513px;
    height: 363px;
    top: 160px;
    left: 774px;
    right: 195px;
    bottom: 153px;
}

.line3 {
    position: absolute;
    width: 94px;
    height: 7px;
    background: #E74040;
    top: 218.5px;
    left: 250px;
    right: 1151px;
    bottom: 450.5px;
}

/* vedio_information */
.Vedio_head {
    position: absolute;
    font-family: 'Montserrat';
    width: 446px;
    height: 50px;
    font-weight: 700;
    font-size: 40px;
    line-height: 50px;
    letter-spacing: 0.2px;
    color: #252B42;
    margin: 0;
    top: 260.5px;
    left: 250px;
    right: 365.5px;
    bottom: 799px;
}

.vedio_paragraph {
    position: absolute;
    font-family: 'Montserrat';
    width: 351px;
    height: 60px;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    letter-spacing: 0.2px;
    color: #737373;
    margin: 0;
    top: 345.5px;
    left: 250px;
    right: 894px;
    bottom: 270.5px;
}

.vedio_lern_more {
    position: absolute;
    font-family: 'Montserrat';
    width: 95px;
    height: 24px;
    font-weight: 700;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #96BB7C;
    margin: 0;
    top: 440.5px;
    left: 250px;
    right: 1163px;
    bottom: 211.5px;
    cursor: pointer;
}

.vedio_lern_more:hover {
    color: #7f9f69;
}

/* Pricing_part */
.pricing_main {
    position: relative;
    top: 580px;
}

.pricing_info {
    position: absolute;
    font-family: 'Montserrat';
    width: 59px;
    height: 24px;
    font-weight: 700;
    margin: 0;
    font-size: 15px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #96BB7C;
    top: 112px;
    left: 250px;
    right: 1183px;
    bottom: 1016px;
}

.pricing_head {
    position: absolute;
    font-family: 'Montserrat';
    width: 406px;
    height: 50px;
    font-size: 40px;
    font-weight: 700;
    line-height: 50px;
    letter-spacing: 0.2px;
    color: #252B42;
    margin: 0;
    top: 146px;
    left: 250px;
    right: 836px;
    bottom: 956px;
}

.pricing_paragraph {
    position: absolute;
    font-family: 'Montserrat';
    width: 469px;
    height: 40px;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    letter-spacing: 0.2px;
    color: #737373;
    margin: 0;
    top: 206px;
    left: 250px;
    right: 773px;
    bottom: 906px;
}

/* 1st_Pricing_card */
.pricing_card1 {
    position: absolute;
    left: 250px;
    right: 1006.5px;
    top: 348px;
    bottom: 494.5px;
}

.sale {
    font-family: 'Montserrat';
    width: 31px;
    height: 24px;
    font-weight: 700;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #FFFFFF;
    margin: 0;
    padding: 0 10px;
    text-align: center;
    background: #E74040;
    box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
    border-radius: 3px;
}

.sale_1 {
    position: absolute;
    top: 378px;
    left: 270.5px;
    right: 173.5px;
    bottom: 750px;
}

/* 2nd_Pricing_card */
.pricing_card2 {
    position: absolute;
    left: 463.5px;
    right: 735.5px;
    top: 348px;
    bottom: 494.5px;
}

.sale_2 {
    position: absolute;
    top: 378px;
    left: 535.5px;
    right: 905.5px;
    bottom: 750px;
}

/* 3rd_Pricing_card */
.pricing_card3 {
    position: absolute;
    left: 734.5px;
    right: 465.5px;
    top: 348px;
    bottom: 494.5px;
}

.sale_3 {
    position: absolute;
    top: 378px;
    left: 802.5px;
    right: 634.5px;
    bottom: 750px;
}

/* 4th_Pricing_card */
.pricing_card4 {
    position: absolute;
    left: 1004.5px;
    right: 195.5px;
    top: 348px;
    bottom: 494.5px;
}

.sale_4 {
    position: absolute;
    top: 378px;
    left: 1070.5px;
    right: 364.5px;
    bottom: 750px;
}

/* Pricing_card_information */
.card1_info1 {
    position: absolute;
    font-family: 'Montserrat';
    width: 139px;
    height: 24px;
    font-weight: 700;
    font-size: 15px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #96BB7C;
    margin: 0;
}

.review {
    position: absolute;
    font-family: 'Montserrat';
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 5px 0 5px 10px;
    width: 50px;
    height: 26px;
    gap: 5px;
    margin: 0;
    background: #2D4059;
    border-radius: 20px;
    font-weight: 400;
    font-size: 12px;
    line-height: 16px;
    letter-spacing: 0.2px;
    color: #FFFFFF;
}

.card1_info2 {
    position: absolute;
    font-family: 'Montserrat';
    width: 190px;
    height: 24px;
    font-weight: 700;
    font-size: 17px;
    line-height: 24px;
    letter-spacing: 0.1px;
    color: #252B42;
    margin: 0;
}

.pricing_card_paragraph {
    position: absolute;
    font-family: 'Montserrat';
    width: 182px;
    height: 40px;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    letter-spacing: 0.2px;
    color: #737373;
    margin: 0;
}

.dowload {
    position: absolute;
    width: 16px;
    height: 16px;
}

.dowload_info {
    position: absolute;
    font-family: 'Montserrat';
    width: 57px;
    height: 24px;
    font-weight: 700;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #737373;
    margin: 0;
}

.price {
    position: absolute;
    font-family: 'Montserrat';
    width: 52px;
    height: 24px;
    font-weight: 700;
    font-size: 16px;
    line-height: 24px;
    text-align: center;
    letter-spacing: 0.1px;
    color: #BDBDBD;
    margin: 0;
}

.sale_price {
    position: absolute;
    width: 45px;
    height: 24px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 24px;
    text-align: center;
    letter-spacing: 0.1px;
    color: #FFAB71;
    margin: 0;
}

.price_learnmore {
    position: absolute;
    font-family: 'Montserrat';
    font-weight: 700;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #96BB7C;
    padding: 10px 20px;
    width: 141.14px;
    height: 44px;
    border: 1px solid #96BB7C;
    border-radius: 37px;
    margin: 0;
    cursor: pointer;
}

.price_learnmore:hover {
    background-color: #9ab58832;
}

.price_learnmore:active {
    background-color: #728d5f33;
}

/* 1st_pricing_card_detail */
.card1_info1_1 {
    position: absolute;
    top: 684px;
    left: 270.5px;
    right: 1087.5px;
    bottom: 444px;
}

.review_1 {
    position: absolute;
    top: 675px;
    left: 418.5px;
    right: 1027.5px;
    bottom: 443px;
}

.card1_info2_1 {
    position: absolute;
    top: 719px;
    left: 270.5px;
    right: 1051.5px;
    bottom: 409px;
}

.pricing_card_paragraph_1 {
    position: absolute;
    top: 753px;
    left: 270.5px;
    right: 1037.5px;
    bottom: 359px;
}

.dowload_1 {
    position: absolute;
    top: 807px;
    left: 270.5px;
    right: 1203.5px;
    bottom: 329px;
}

.dowload_info_1 {
    position: absolute;
    top: 803px;
    left: 296.5px;
    right: 1136.5px;
    bottom: 325px;
}

.price_1 {
    position: absolute;
    top: 842px;
    left: 273.5px;
    right: 1164.5px;
    bottom: 286px;
}

.sale_price_1 {
    position: absolute;
    top: 842px;
    left: 333.5px;
    right: 1114.5px;
    bottom: 286px;
}

.price_learnmore_1 {
    position: absolute;
    top: 881px;
    left: 270.5px;
    right: 1117.5px;
    bottom: 237px;
}

/* 1st_card_icon_detail */
.heart {
    box-sizing: border-box;
    position: absolute;
    left: 294.5px;
    right: 6.24%;
    width: 18px;
    top: 580px;
    padding: 11px 26px 25px 10px;
    bottom: 9.38%;
    color: #000000;
    background-color: aliceblue;
    border: 0.625px solid #ffffff;
    border-radius: 150px;
    opacity: 0.0;
    cursor: pointer;
}

.icon_div:hover i {
    opacity: 1.0;
}

.heart:hover {
    background-color: #d1d0d0d0;
    border-color: #a199998e;
    color: #000000;
}

.cart {
    box-sizing: border-box;
    position: absolute;
    left: 351.5px;
    right: 6.24%;
    width: 18px;
    top: 580px;
    padding: 11px 28px 25px 10px;
    bottom: 9.38%;
    color: #000000;
    background-color: aliceblue;
    border: 0.625px solid #ffffff;
    border-radius: 150px;
    opacity: 0.0;
    cursor: pointer;
}

.cart:hover {
    background-color: #d1d0d0d0;
    border-color: #a199998e;
    color: #000000;
}

.eye {
    box-sizing: border-box;
    position: absolute;
    left: 409px;
    right: 6.24%;
    width: 18px;
    top: 580px;
    padding: 11px 28px 25px 10px;
    bottom: 9.38%;
    color: #000000;
    background-color: aliceblue;
    border: 0.625px solid #ffffff;
    border-radius: 150px;
    opacity: 0.0;
    cursor: pointer;
}

.eye:hover {
    background-color: #d1d0d0d0;
    border-color: #a199998e;
    color: #000000;
}

/* 2nd_pricing_card_detail */
.pricing_card2 {
    position: absolute;
    left: 514px;
}

.card1_info1_2 {
    position: absolute;
    top: 684px;
    left: 535.5px;
    right: 839.5px;
    bottom: 444px;
}

.review_2 {
    position: absolute;
    top: 675px;
    left: 650.5px;
    right: 769.5px;
    bottom: 443px;
}

.card1_info2_2 {
    position: absolute;
    top: 719px;
    left: 535.5px;
    right: 772.5px;
    bottom: 409px;
}

.pricing_card_paragraph_2 {
    position: absolute;
    top: 753px;
    left: 535.5px;
    right: 769.5px;
    bottom: 359px;
}

.dowload_2 {
    position: absolute;
    top: 807px;
    left: 535.5px;
    right: 935.5px;
    bottom: 329px;
}

.dowload_info_2 {
    position: absolute;
    top: 803px;
    left: 562.5px;
    right: 868.5px;
    bottom: 325px;
}

.price_2 {
    position: absolute;
    top: 842px;
    left: 538.5px;
    right: 896.5px;
    bottom: 286px;
}

.sale_price_2 {
    position: absolute;
    top: 842px;
    left: 598.5px;
    right: 846.5px;
    bottom: 286px;
}

.price_learnmore_2 {
    position: absolute;
    top: 881px;
    left: 535.5px;
    right: 810.5px;
    bottom: 237px;
}

/* 2nd_card_icon_detail */
.heart_2 {
    box-sizing: border-box;
    position: absolute;
    left: 551.5px;
    right: 6.24%;
    width: 18px;
    top: 580px;
    padding: 11px 26px 25px 10px;
    bottom: 9.38%;
    color: #000000;
    background-color: aliceblue;
    border: 0.625px solid #ffffff;
    border-radius: 150px;
    opacity: 0.0;
    cursor: pointer;
}

.icon_div_2:hover i {
    opacity: 1.0;
}

.heart_2:hover {
    background-color: #d1d0d0d0;
    border-color: #a199998e;
    color: #000000;
}

.cart_2 {
    box-sizing: border-box;
    position: absolute;
    left: 608.5px;
    right: 6.24%;
    width: 18px;
    top: 580px;
    padding: 11px 28px 25px 10px;
    bottom: 9.38%;
    color: #000000;
    background-color: aliceblue;
    border: 0.625px solid #ffffff;
    border-radius: 150px;
    opacity: 0.0;
    cursor: pointer;
}

.cart_2:hover {
    background-color: #d1d0d0d0;
    border-color: #a199998e;
    color: #000000;
}

.eye_2 {
    box-sizing: border-box;
    position: absolute;
    left: 673px;
    right: 6.24%;
    width: 18px;
    top: 580px;
    padding: 11px 28px 25px 10px;
    bottom: 9.38%;
    color: #000000;
    background-color: aliceblue;
    border: 0.625px solid #ffffff;
    border-radius: 150px;
    opacity: 0.0;
    cursor: pointer;
}

.eye_2:hover {
    background-color: #d1d0d0d0;
    border-color: #a199998e;
    color: #000000;
}

/* 3rd_pricing_card_detail */
.pricing_card3 {
    position: absolute;
    left: 780px;
}

.card1_info1_3 {
    position: absolute;
    top: 684px;
    left: 802.5px;
    right: 566.5px;
    bottom: 444px;
}

.review_3 {
    position: absolute;
    top: 675px;
    left: 940.5px;
    right: 498.5px;
    bottom: 443px;
}

.card1_info2_3 {
    position: absolute;
    top: 719px;
    left: 802.5px;
    right: 525.5px;
    bottom: 409px;
}

.pricing_card_paragraph_3 {
    position: absolute;
    top: 753px;
    left: 802.5px;
    right: 498.5px;
    bottom: 359px;
}

.dowload_3 {
    position: absolute;
    top: 807px;
    left: 802.5px;
    right: 664.5px;
    bottom: 329px;
}

.dowload_info_3 {
    position: absolute;
    top: 803px;
    left: 830.5px;
    right: 597.5px;
    bottom: 325px;
}

.price_3 {
    position: absolute;
    top: 842px;
    left: 805.5px;
    right: 625.5px;
    bottom: 286px;
}

.sale_price_3 {
    position: absolute;
    top: 842px;
    left: 866.5px;
    right: 575.5px;
    bottom: 286px;
}

.price_learnmore_3 {
    position: absolute;
    top: 881px;
    left: 802.5px;
    right: 539.36px;
    bottom: 237px;
}

/* 3rd_card_icon_detail */
.heart_3 {
    box-sizing: border-box;
    position: absolute;
    left: 817.5px;
    right: 6.24%;
    width: 18px;
    top: 580px;
    padding: 11px 26px 25px 10px;
    bottom: 9.38%;
    color: #000000;
    background-color: aliceblue;
    border: 0.625px solid #ffffff;
    border-radius: 150px;
    opacity: 0.0;
    cursor: pointer;
}

.icon_div_3:hover i {
    opacity: 1.0;
}

.heart_3:hover {
    background-color: #d1d0d0d0;
    border-color: #a199998e;
    color: #000000;
}

.cart_3 {
    box-sizing: border-box;
    position: absolute;
    left: 879.5px;
    right: 6.24%;
    width: 18px;
    top: 580px;
    padding: 11px 28px 25px 10px;
    bottom: 9.38%;
    color: #000000;
    background-color: aliceblue;
    border: 0.625px solid #ffffff;
    border-radius: 150px;
    opacity: 0.0;
    cursor: pointer;
}

.cart_3:hover {
    background-color: #d1d0d0d0;
    border-color: #a199998e;
    color: #000000;
}

.eye_3 {
    box-sizing: border-box;
    position: absolute;
    left: 943px;
    right: 6.24%;
    width: 18px;
    top: 580px;
    padding: 11px 28px 25px 10px;
    bottom: 9.38%;
    color: #000000;
    background-color: aliceblue;
    border: 0.625px solid #ffffff;
    border-radius: 150px;
    opacity: 0.0;
    cursor: pointer;
}

.eye_3:hover {
    background-color: #d1d0d0d0;
    border-color: #a199998e;
    color: #000000;
}


/* 4th_pricing_card_detail */
.pricing_card4 {
    position: absolute;
    inset: 348px 195.5px 494.5px 1004.5px;
    right: 0px;
    left: 1046px;
}

.card1_info1_4 {
    position: absolute;
    top: 684px;
    left: 1070.5px;
    right: 298.5px;
    bottom: 444px;
}

.review_4 {
    position: absolute;
    top: 675px;
    left: 1193.5px;
    right: 228.5px;
    bottom: 443px;
}

.card1_info2_4 {
    position: absolute;
    top: 719px;
    left: 1070.5px;
    right: 241.5px;
    bottom: 409px;
}

.pricing_card_paragraph_4 {
    position: absolute;
    top: 753px;
    left: 1070.5px;
    right: 228.5px;
    bottom: 359px;
}

.dowload_4 {
    position: absolute;
    top: 807px;
    left: 1070.5px;
    right: 394.5px;
    bottom: 329px;
}

.dowload_info_4 {
    position: absolute;
    top: 803px;
    left: 1098.5px;
    right: 327.5px;
    bottom: 325px;
}

.price_4 {
    position: absolute;
    top: 842px;
    left: 1073.5px;
    right: 355.5px;
    bottom: 286px;
}

.sale_price_4 {
    position: absolute;
    top: 842px;
    left: 1135.5px;
    right: 305.5px;
    bottom: 286px;
}

.price_learnmore_4 {
    position: absolute;
    top: 881px;
    left: 1070.5px;
    right: 269.36px;
    bottom: 237px;
}

/* 3rd_card_icon_detail */
.heart_4 {
    box-sizing: border-box;
    position: absolute;
    left: 1085.5px;
    right: 6.24%;
    width: 18px;
    top: 580px;
    padding: 11px 26px 25px 10px;
    bottom: 9.38%;
    color: #000000;
    background-color: aliceblue;
    border: 0.625px solid #ffffff;
    border-radius: 150px;
    opacity: 0.0;
    cursor: pointer;
}

.icon_div_4:hover i {
    opacity: 1.0;
}

.heart_4:hover {
    background-color: #d1d0d0d0;
    border-color: #a199998e;
    color: #000000;
}

.cart_4 {
    box-sizing: border-box;
    position: absolute;
    left: 1147.5px;
    right: 6.24%;
    width: 18px;
    top: 580px;
    padding: 11px 28px 25px 10px;
    bottom: 9.38%;
    color: #000000;
    background-color: aliceblue;
    border: 0.625px solid #ffffff;
    border-radius: 150px;
    opacity: 0.0;
    cursor: pointer;
}

.cart_4:hover {
    background-color: #d1d0d0d0;
    border-color: #a199998e;
    color: #000000;
}

.eye_4 {
    box-sizing: border-box;
    position: absolute;
    left: 1210px;
    right: 6.24%;
    width: 18px;
    top: 580px;
    padding: 11px 28px 25px 10px;
    bottom: 9.38%;
    color: #000000;
    background-color: aliceblue;
    border: 0.625px solid #ffffff;
    border-radius: 150px;
    opacity: 0.0;
    cursor: pointer;
}

.eye_4:hover {
    background-color: #d1d0d0d0;
    border-color: #a199998e;
    color: #000000;
}


/* team Part */
.team {
    position: relative;
    top: 1450px;
}

.team_head {
    position: absolute;
    font-family: 'Montserrat';
    width: 93px;
    height: 24px;
    font-weight: 700;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #96BB7C;
    margin: 0 0;
    top: 160px;
    left: 250px;
    right: 1149px;
    bottom: 681px;
}

.team_info {
    position: absolute;
    font-family: 'Montserrat';
    width: 420px;
    height: 50px;
    font-weight: 700;
    font-size: 40px;
    line-height: 50px;
    letter-spacing: 0.2px;
    color: #252B42;
    margin: 0 0;
    top: 194px;
    left: 250px;
    right: 822px;
    bottom: 621px;
}

.team_paragraph {
    position: absolute;
    font-family: 'Montserrat';
    width: 469px;
    height: 40px;
    font-weight: 400;
    font-size: 15px;
    line-height: 20px;
    letter-spacing: 0.2px;
    color: #737373;
    margin: 0 0;
    top: 254px;
    left: 250px;
    right: 773px;
    bottom: 571px;
}

/* team_information_with_1st_images */
.Team_information {
    position: absolute;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 408px;
    height: 378.01px;
    background: #FFFFFF;
    top: 390px;
    left: 222px;
    right: 737px;
    bottom: 96.99px;
}

.team_man_1 {
    position: absolute;
    height: 128px;
    top: 25px;
    right: 190px;
    right: 190px;
    bottom: 255.01px;
}

.team_paragraph {
    position: absolute;
    width: 382px;
    height: 60px;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    letter-spacing: 0.2px;
    color: #737373;
    margin: 0 0;
}

.team_paragraph_1 {
    font-family: 'Montserrat';
    width: 320px;
    height: 60px;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    text-align: center;
    letter-spacing: 0.2px;
    color: #737373;
    position: absolute;
    margin: 0 0;
    top: 183px;
    right: 69px;
    right: 69px;
    bottom: 135.01px;
}

.star {
    position: absolute;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    padding: 0px;
    gap: 5px;
    width: 130.07px;
    height: 22.01px;
    margin: 0 0;
    top: 258px;
    right: 188.97px;
    right: 188.97px;
    bottom: 98px;
}

.team_man_name {
    position: absolute;
    font-family: 'Montserrat';
    width: 105px;
    height: 24px;
    font-weight: 700;
    font-size: 16px;
    line-height: 24px;
    text-align: center;
    letter-spacing: 0.1px;
    color: #252B42;
    margin: 0 0;
    top: 295.01px;
    right: 201.5px;
    right: 201.5px;
    bottom: 59px;
}

.team_man_detail {
    position: absolute;
    font-family: 'Montserrat';
    width: 65px;
    height: 24px;
    font-weight: 700;
    font-size: 14px;
    line-height: 24px;
    text-align: center;
    letter-spacing: 0.2px;
    color: #737373;
    margin: 0 0;
    top: 324.01px;
    right: 221.5px;
    right: 221.5px;
    bottom: 30px;
}

/* team_man_2nd_Information */
.Team_information_2 {
    position: absolute;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 408px;
    height: 378.01px;
    background: #FFFFFF;
    top: 390px;
    left: 595px;
    right: 737px;
    bottom: 96.99px;
}

/* team_man_3rd_Information */
.Team_information_3 {
    position: absolute;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 408px;
    height: 378.01px;
    background: #FFFFFF;
    top: 390px;
    left: 971px;
    right: 737px;
    bottom: 96.99px;
}

/* Contact_information */
.contact_main {
    position: relative;
    width: 1519px;
    height: 594px;
    background: #FFF2F3;
    top: 2287px;
}

.news_info {
    position: absolute;
    width: 92px;
    height: 24px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 700;
    font-size: 15px;
    line-height: 24px;
    text-align: center;
    letter-spacing: 0.2px;
    color: #96BB7C;
    margin: 0 0;
    top: 160px;
    left: 679px;
}

.cont_head {
    position: absolute;
    width: 251px;
    height: 32px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 700;
    font-size: 24px;
    line-height: 32px;
    text-align: center;
    letter-spacing: 0.1px;
    color: #252B42;
    margin: 0 0;
    top: 194px;
    left: 594.5px;
}

.cont_paragraph {
    position: absolute;
    width: 469px;
    height: 40px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 20px;
    text-align: center;
    letter-spacing: 0.2px;
    color: #737373;
    top: 236px;
    left: 485.5px;
}

.email {
    box-sizing: border-box;
    position: absolute;
    left: 376px;
    top: 356px;
    background: #F9F9F9;
    border: 1px solid #E6E6E6;
    border-radius: 5px;
    width: 37.5%;
    padding: 20px 20px;
    height: 28px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 28px;
    letter-spacing: 0.2px;
    color: #737373;
}

.cont_btn {
    box-sizing: border-box;
    position: absolute;
    left: 941px;
    top: 356px;
    background: #96BB7C;
    border: 1px solid #E6E6E6;
    border-radius: 0px 5px 5px 0px;
    width: 130px;
    height: 42.5px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 28px;
    text-align: center;
    letter-spacing: 0.2px;
    color: #FFFFFF;
    cursor: pointer;
}

.cont_btn:hover {
    background-color: #759c5d;
}

.cont_btn:active {
    background-color: #759c5de1;
}

/* Footer_part */
.footer_flex {
    position: absolute;
    display: flex;
    top: 4430.5px;
    left: 195px;
}

.footer_div_2 {
    position: absolute;
    left: 165px;
    width: 150px;
    margin: 0;
}

.footer_div_3 {
    position: absolute;
    left: 353px;
    width: 150px;
    margin: 0;
}

.footer_div_4 {
    position: absolute;
    left: 553px;
    width: 150px;
    margin: 0;
}

.footer_head_6 {
    margin: 10px 0;
    width: 151.5px;
    height: 24px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 700;
    font-size: 15px;
    line-height: 24px;
    letter-spacing: 0.2px;
    cursor: pointer;
    color: #737373;
}

.footer_head_5 {
    margin-bottom: 20px;
    width: 115px;
    height: 24px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 24px;
    letter-spacing: 0.1px;
    color: #252B42;
}

.footer_head_6:hover {
    color: #252B42;
}

.footer_div_5 {
    position: absolute;
    left: 800px;
    width: 150px;
    margin: 0;
}

/* icon_Information */

.phone {
    position: absolute;
    top: 3px;
    color: #96BB7C;
    left: -35px;
    font-size: 23px;
}

.icon1_txt {
    margin: 0;
    position: absolute;
    top: 94px;
    left: 35px;
    width: 115px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #737373;
    cursor: pointer;
}

.icon1_txt:hover {
    color: #252B42;
}

.location {
    position: absolute;
    top: 0px;
    color: #96BB7C;
    left: -35px;
    font-size: 30px;
}

.icon2_txt {
    margin: 0;
    position: absolute;
    width: 282px;
    top: 174px;
    left: 35px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #737373;
    cursor: pointer;
}

.icon2_txt:hover {
    color: #252B42;
}

.email_2 {
    position: absolute;
    top: 0px;
    color: #96BB7C;
    left: -35px;
    font-size: 25px;
}

.icon3_txt {
    margin: 0;
    position: absolute;
    top: 135px;
    left: 35px;
    width: 282px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #737373;
    cursor: pointer;
}

.icon3_txt:hover {
    color: #252B42;
}

/* footer_end */
.footer_last_div {
    position: absolute;
    width: 1519px;
    height: 74px;
    background: #FAFAFA;
    top: 4682px;
    left: 0;
}

.footer_txt {
    position: absolute;
    width: 359px;
    height: 24px;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 700;
    font-size: 14px;
    line-height: 24px;
    letter-spacing: 0.2px;
    color: #737373;
    top: -5px;
    left: 195px;
}

.facebook {
    position: absolute;
    left: 1070px;
    top: 24px;
    color: #96BB7C;
    font-size: 27px;
    cursor: pointer;
}

.facebook:hover {
    color: #688258d9;
}

.facebook:active {
    color: #759c5de1;
}

.insta {

    position: absolute;
    left: 1125.5px;
    top: 24px;
    color: #96BB7C;
    font-size: 27px;
    cursor: pointer;
}

.insta:hover {
    color: #688258d9;
}

.insta:active {
    color: #759c5de1;
}

.twitter {
    position: absolute;
    left: 1179.5px;
    top: 24px;
    color: #96BB7C;
    font-size: 27px;
    cursor: pointer;
}

.twitter:hover {
    color: #688258d9;
}

.twitter:active {
    color: #759c5de1;
}
    </style>
</head>

<body>
    <div class="main">
        <!--Footer  -->
        <div class="container">

            <ul>
                <h3 class="head">BrandName</h3>
                <li class="home1"><a href="#home" class="home2">Home</a></li>
                <li class="product1"><a href="#invester" class="product2">Product</a></li>
                <li class="pricing1"><a href="#contact" class="pricing2">Pricing</a></li>
                <li class="contact1"><a href="#blog" class="contact2">Contact</a></li>
            </ul>
        </div>

        <!-- Home Page Right_Part -->
        <div class="maininfo">
            <img src="Rectangle 7.png" alt="Rectangle Images" class="rect">
            <img src="Rectangle 8.png" alt="Rectangle Images" class="rect_1">
            <button type="button" name="login" class="but1">Login</button>
            <button type="button" name="Join" class="but2">JOIN US<img src="Vector1.png" alt=""></button>
            <div>
                <img src="none.png" alt="none Images" class="main_image">
            </div>

            <!-- Home Page Left_Part -->
            <div class="left_part">
                <h6 class="info1">Online traning</h6>
                <h1 class="info2"><b>25K+ STUDENTS <br> TRUST US</b> </h1>
                <h4 class="info3">Our goal is to make online education work <br> for everyone</h4>
                <button type="button" name="Join" class="but_get_quote">Get Quote Now</button>
                <button type="button" name="Join" class="but_learn_more">Learn More</button>
            </div>

            <!-- card_Home Page -->
            <div class="card_main_div">
                <div class="card1">
                    <img src="desktop_screen.png" alt="Desktop Images" class="card1_image">
                    <h3 class="card_info1">Certified Teacher</h3>
                    <img src="line.png" alt="red Line Image" class="line">
                    <p class="card_paragraph">The gradual accumulation of <br>information about atomic and
                        <br>small-scale
                        behaviour...
                    </p>
                </div>

                <div class="card2">
                    <img src="telescope.png" alt="Telescope Images" class="card1_image">
                    <h3 class="card_info1">2,769 online courses</h3>
                    <img src="line.png" alt="red Line Image" class="line">
                    <p class="card_paragraph">The gradual accumulation of <br>information about atomic and
                        <br>small-scale
                        behaviour...
                    </p>
                </div>

                <div class="card3">
                    <img src="flask.png" alt="Flask Images" class="card1_image">
                    <h3 class="card_info1">2,769 online courses</h3>
                    <img src="line.png" alt="red Line Image" class="line">
                    <p class="card_paragraph">The gradual accumulation of <br>information about atomic and
                        <br>small-scale
                        behaviour...
                    </p>
                </div>
            </div>

            <!-- Thumbail_2nd _part -->
            <div class="main_body">
                <div>
                    <div class="thumbail_main">
                        <div class="thumbail_main_div">
                            <img src="thumbail.png" alt="Thubail Image" class="thumbail">
                            <img src="line.png" alt="Line Image" class="line2">
                            <h2 class="thumbail_head">Approdable <br>Packages</h2>
                            <p class="thumbail_paragraph">Problem tryping to reslove the conflict between <br>the two
                                major
                                of
                                Classical physics: <br>Newtonian mechanics
                            </p>
                            <h6 class="thumbail_lern_more">Learn More > </h6>
                        </div>
                    </div>

                </div>


                <!-- video_part -->
                <div class="vedio_main">

                    <img src="vedio image.png" alt="Vedio image" class="vedio_img">
                    <img src="line.png" alt="Line Image" class="line3">
                    <h2 class="Vedio_head">Approdable Packages</h2>
                    <p class="vedio_paragraph">Problem tryping to reslove the conflict between <br>the two major of
                        Classical physics: <br>Newtonian mechanics
                    </p>
                    <h6 class="vedio_lern_more">Learn More > </h6>
                </div>

                <!-- Pricing_part -->
                <div class="pricing_main">
                    <h6 class="pricing_info">Courses</h6>
                    <h2 class="pricing_head">Video in Live Action</h2>
                    <p class="pricing_paragraph">Problem tryping to reslove the conflict between <br>the two major of
                        Classical physics : Newtonian mechanics
                    </p>

                    <!-- 1st_pricing_card -->
                    <div>
                        <div class="icon_div">
                            <img src="product_cover1.png" alt="Product Cover 1st Image" class="pricing_card1">
                            <h6 class="sale sale_1">sale</h6>
                            <!-- icon -->
                            <i class="fa-regular fa-heart heart"></i>
                            <i class="fa-solid fa-cart-shopping cart"></i>
                            <i class="fa-solid fa-eye eye"></i>
                        </div>
                        <h6 class="card1_info1 card1_info1_1">Expert instruction</h6>
                        <h6 class="review review_1">&#11088; 4.9</h6>
                        <h5 class="card1_info2 card1_info2_1">Every Client Matters</h5>
                        <p class="pricing_card_paragraph pricing_card_paragraph_1">We focus on ergonomics <br>and
                            meeting
                            you....</p>
                        <img src="dowload symbol.png" alt="dowload Image" class="dowload dowload_1">
                        <h6 class="dowload_info dowload_info_1">15 Sales</h6>
                        <h5 class="price price_1">$16.48</h5>
                        <h5 class="sale_price sale_price_1">$6.48</h5>
                        <button type="button" name="button" class="price_learnmore price_learnmore_1">Learn More
                            ></button>
                    </div>

                    <!-- 2nd_pricing_card -->
                    <div>
                        <div class="icon_div_2">
                            <img src="product_cover2.png" alt="Product Cover 2nd Image" class="pricing_card2">
                            <h6 class="sale sale_2">sale</h6>
                            <!-- icon -->
                            <i class="fa-regular fa-heart heart_2"></i>
                            <i class="fa-solid fa-cart-shopping cart_2"></i>
                            <i class="fa-solid fa-eye eye_2"></i>
                        </div>

                        <h6 class="card1_info1 card1_info1_2">Book liberary</h6>
                        <h6 class="review review_2">&#11088; 4.9</h6>
                        <h5 class="card1_info2 card1_info2_2">Approdable Packages</h5>
                        <p class="pricing_card_paragraph pricing_card_paragraph_2">We focus on ergonomics <br>and
                            meeting
                            you....</p>
                        <img src="dowload symbol.png" alt="dowload Image" class="dowload dowload_2">
                        <h6 class="dowload_info dowload_info_2">15 Sales</h6>
                        <h5 class="price price_2">$16.48</h5>
                        <h5 class="sale_price sale_price_2">$6.48</h5>
                        <button type="button" name="button" class="price_learnmore price_learnmore_2">Learn More
                            ></button>
                    </div>

                    <!-- 3rd_pricing_card -->
                    <div>
                        <div class="icon_div_3">
                            <img src="product_cover3.png" alt="Product Cover 3rd Image" class="pricing_card3">
                            <h6 class="sale sale_3">sale</h6>
                            <!-- icon -->
                            <i class="fa-regular fa-heart heart_3"></i>
                            <i class="fa-solid fa-cart-shopping cart_3"></i>
                            <i class="fa-solid fa-eye eye_3"></i>
                        </div>

                        <h6 class="card1_info1 card1_info1_3">Lifetime Access</h6>
                        <h6 class="review review_3">&#11088; 4.9</h6>
                        <h5 class="card1_info2 card1_info2_3">Watch our courses</h5>
                        <p class="pricing_card_paragraph pricing_card_paragraph_3">We focus on ergonomics <br>and
                            meeting
                            you....</p>
                        <img src="dowload symbol.png" alt="dowload Image" class="dowload dowload_3">
                        <h6 class="dowload_info dowload_info_3">15 Sales</h6>
                        <h5 class="price price_3">$16.48</h5>
                        <h5 class="sale_price sale_price_3">$6.48</h5>
                        <button type="button" name="button" class="price_learnmore price_learnmore_3">Learn More
                            ></button>
                    </div>

                    <!-- 4th_pricing_card -->
                    <div>
                        <div class="icon_div_4">
                            <img src="product_cover4.png" alt="Product Cover 4th Image" class="pricing_card4">
                            <h6 class="sale sale_4">sale</h6>
                            <!-- icon -->
                            <i class="fa-regular fa-heart heart_4"></i>
                            <i class="fa-solid fa-cart-shopping cart_4"></i>
                            <i class="fa-solid fa-eye eye_4"></i>
                        </div>

                        <h6 class="card1_info1 card1_info1_4">Book Liberary</h6>
                        <h6 class="review review_4">&#11088; 4.9</h6>
                        <h5 class="card1_info2 card1_info2_4">Our Popular Courses</h5>
                        <p class="pricing_card_paragraph pricing_card_paragraph_4">We focus on ergonomics <br>and
                            meeting
                            you....</p>
                        <img src="dowload symbol.png" alt="dowload Image" class="dowload dowload_4">
                        <h6 class="dowload_info dowload_info_4">15 Sales</h6>
                        <h5 class="price price_4">$16.48</h5>
                        <h5 class="sale_price sale_price_4">$6.48</h5>
                        <button type="button" name="button" class="price_learnmore price_learnmore_4">Learn More
                            ></button>
                    </div>

                </div>
            </div>
            <div class="team">
                <!-- Team Part -->
                <div>
                    <h6 class="team_head">Testimonials</h6>
                    <h2 class="team_info">Our Popular Courses</h2>
                    <p class="team_paragraph">Problems tryping to resolve the conflict between <br>the two major realms
                        of
                        Classical physics : Newtonian mechanics</p>

                    <!-- Team_information -->
                    <div class="Team_information">
                        <img src="team_images_1.png" alt="team_images_1" class="team_man_1">
                        <p class="team_paragraph_1">Slate helps you see how many more days <br>you need to work to reach
                            your
                            financial <br>goal for the month and year.</p>
                        <img src="star.png" alt="Star Images" class="star">
                        <h5 class="team_man_name">Regina Miles</h5>
                        <h6 class="team_man_detail">Designer</h6>
                    </div>
                    <div class="Team_information_2">
                        <img src="team_images_2.png" alt="team_images_1" class="team_man_1">
                        <p class="team_paragraph_1">Slate helps you see how many more days <br>you need to work to reach
                            your
                            financial <br>goal for the month and year.</p>
                        <img src="star.png" alt="Star Images" class="star">
                        <h5 class="team_man_name">Regina Miles</h5>
                        <h6 class="team_man_detail">Designer</h6>
                    </div>
                    <div class="Team_information_3">
                        <img src="team_images_1.png" alt="team_images_1" class="team_man_1">
                        <p class="team_paragraph_1">Slate helps you see how many more days <br>you need to work to reach
                            your
                            financial <br>goal for the month and year.</p>
                        <img src="star.png" alt="Star Images" class="star">
                        <h5 class="team_man_name">Regina Miles</h5>
                        <h6 class="team_man_detail">Designer</h6>
                    </div>
                </div>
            </div>

            <!-- Contact_information -->
            <div class="contact_main">
                <h6 class="news_info">NewsLetter</h6>
                <h3 class="cont_head">Our Expert Teacher</h3>                
                <p class="cont_paragraph">Problems tryping to reslove the conflict between <br>the two major realms of
                    Classical physics : Newtonian mechanics</p>
                <input type="email" id="email" placeholder="Your Email" class="email">
                <button type="button" id="button" class="cont_btn">Subscribe</button>
            </div>

            <!--  Footer_Information -->
            <div class="footer_flex">
                <div class="footer_div_1">
                    <h5 class="footer_head_5">Company Info</h5>
                    <h6 class="footer_head_6">About us</h6>
                    <h6 class="footer_head_6">Carrier</h6>
                    <h6 class="footer_head_6">we are hiring</h6>
                    <h6 class="footer_head_6">Blog</h6>
                </div>
                <div class="footer_div_2">
                    <h5 class="footer_head_5">Legal</h5>
                    <h6 class="footer_head_6">About us</h6>
                    <h6 class="footer_head_6">Carrier</h6>
                    <h6 class="footer_head_6">we are hiring</h6>
                    <h6 class="footer_head_6">Blog</h6>
                </div>
                <div class="footer_div_3">
                    <h5 class="footer_head_5">Features</h5>
                    <h6 class="footer_head_6">Business Marketing</h6>
                    <h6 class="footer_head_6">User Analytic</h6>
                    <h6 class="footer_head_6">Live Chat</h6>
                    <h6 class="footer_head_6">Unlimitted Support</h6>
                </div>
                <div class="footer_div_4">
                    <h5 class="footer_head_5">Resources</h5>
                    <h6 class="footer_head_6">IOS & Android</h6>
                    <h6 class="footer_head_6">Watch a Demo</h6>
                    <h6 class="footer_head_6">Customers</h6>
                    <h6 class="footer_head_6">API</h6>
                </div>
                <div class="footer_div_5">
                    <h5 class="footer_head_5">Get In Touch</h5>
                    <p class="icon1_txt"><i class="fa-solid fa-phone phone"></i>(480)-555-0103</p>

                    <p class="icon3_txt"><i class="fa-solid fa-envelope email_2"></i>debra.holt@example.com</p>

                    <p class="icon2_txt"><i class="fa-solid fa-location-dot location"></i>4517 Washington Ave.
                        Manchester,Kenf</p>
                </div>
            </div>
        </div>
               
        <!-- footer -->
        <div class="footer_last_div">
            <h6 class="footer_txt">Made With Love By Figmaland All Right Reserved</h6>
            <i class="fa-brands fa-facebook facebook"></i>
            <i class="fa-brands fa-instagram insta"></i>
            <i class="fa-brands fa-twitter twitter"></i>
        </div>
    </div>
</body>

</html>
