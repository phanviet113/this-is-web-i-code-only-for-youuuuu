import turtle

# Mật khẩu đúng
correct_password = "iuemnhieu"

# Yêu cầu người dùng nhập mật khẩu
password = input("Nhập mật khẩu để mở khóa: ")

if password == correct_password:
    t = turtle.Turtle()
    t.pensize(4)
    t.shape("turtle")
    turtle.bgcolor("black")

    def go(x, y):
        t.penup()
        t.goto(x, y)
        t.pendown()

    t.pencolor("DarkKhaki")
    t.fillcolor("Khaki")

    go(40.03, -167.53)
    t.begin_fill()
    t.seth(104.91)
    t.circle(120.54, 29.94)
    t.seth(49.57)
    t.circle(-315.30, 15.58)
    t.seth(33.99)
    t.circle(172.07, 64.94)
    t.seth(185.9)
    t.circle(227.51, 53.26)
    t.seth(239.17)
    t.circle(99.15, 72.41)
    t.seth(213.64)
    t.circle(74.25, 50.32)
    t.seth(336.29)
    t.circle(108.41, 47.43)
    t.end_fill()

    go(-37.02, -69.53)
    t.begin_fill()
    t.seth(98.75)
    t.circle(-121.74, 54.75)
    t.seth(131.6)
    t.circle(187.54, 48.16)
    t.seth(253.4)
    t.circle(134.51, 95.25)
    t.end_fill()

    t.pencolor("MediumVioletRed")
    t.fillcolor("HotPink")

    go(69.69, -55.52)
    t.begin_fill()
    t.seth(184.72)
    t.circle(90.59, 53.66)
    t.seth(127.63)
    t.circle(111.93, 45.5)
    t.seth(234.89)
    t.circle(80.10, 70.23)
    t.seth(9.8)
    t.circle(152.91, 31.68)
    t.seth(311.3)
    t.circle(108.05, 42.6)
    t.seth(58.45)
    t.circle(88.07, 63.09)
    t.end_fill()

    go(16.3, -99.27)
    t.begin_fill()
    t.seth(90)
    t.circle(19.5)
    t.end_fill()

    def hojas(angulo):
        t.begin_fill()
        t.seth(angulo)
        t.circle(75.61,121.08)
        t.seth(angulo+175.63)
        t.circle(72.70, 129.82)
        t.end_fill()

    t.pencolor("DarkGreen")
    t.fillcolor("LimeGreen")

    go(-79.30, 110.03)
    hojas(165.01)
    go(-122.12, 151)
    hojas(79.67)

    t.fillcolor("LawnGreen")

    go(-100.51, 123.98)
    hojas(119.46)
    go(-90.46, 135.14)
    hojas(22.07)

    def flor(x, y):
        go(x, y)
        t.begin_fill()
        t.seth(330.2)
        t.circle(22.66, 236.14)
        t.seth(42.2)
        t.circle(22.66, 236.14)
        t.seth(114.2)
        t.circle(22.66, 236.14)
        t.seth(186.2)
        t.circle(22.66, 236.14)
        t.seth(258.2)
        t.circle(22.66, 236.14)
        t.end_fill()
        t.pencolor("Gold")
        t.fillcolor("Gold")
        go(x-4.81, y+20.88)
        t.begin_fill()
        t.seth(90)
        t.circle(22.5)
        t.end_fill()

    t.pencolor("Tomato")
    t.fillcolor("Orange")
    flor(155.36, 115.58)
    t.pencolor("SteelBlue")
    t.fillcolor("DarkTurquoise")
    flor(60.97, 170)
    t.pencolor("IndianRed")
    t.fillcolor("LightSalmon")
    flor(-45.377, 120)
    t.pencolor("MediumOrchid")
    t.fillcolor("Violet")
    flor(-11.60, 41.39)
    t.pencolor("DarkGray")
    t.fillcolor("White")
    flor(65.71, 85.27)

    t.color("Chocolate")
    go(100, -250)
    t.write("Hôm nay là ngày 21 tháng 11 năm 2024, và anh muốn viết những dòng này cho em từ bây giờ vì anh muốn chuẩn bị thật tốt cho mọi thứ. Em là người đặc biệt với anh, và anh cũng muốn món quà này dành cho em phải thật sự đặc biệt.

Anh hy vọng rằng vào ngày 3/12, chúng ta sẽ chính thức bước vào một mối quan hệ mới. Nếu mọi thứ diễn ra tốt đẹp, đó sẽ là thời điểm mà chúng ta bắt đầu cùng nhau, không chỉ là những cuộc trò chuyện nữa mà là sự đồng hành thật sự. Anh rất vui và hạnh phúc vì em đã đến bên anh, cho anh cơ hội để yêu thương và quan tâm em.

Anh hiểu rằng trong một mối quan hệ, không phải lúc nào cũng hoàn hảo. Sẽ có những lúc chúng ta không đồng quan điểm, nhưng anh mong rằng thay vì cãi nhau, chúng ta sẽ luôn tìm cách trò chuyện và hiểu nhau hơn. Nếu em gặp phải bất kỳ điều gì khiến em buồn hoặc khó chịu, đừng ngần ngại chia sẻ với anh. Anh luôn sẵn sàng lắng nghe và ở đây để cùng em vượt qua mọi khó khăn.

Cuộc sống sẽ không phải lúc nào cũng dễ dàng. Công việc, học tập, gia đình… những vấn đề đó đôi khi có thể làm chúng ta cảm thấy căng thẳng và mệt mỏi. Nhưng anh hy vọng chúng ta sẽ luôn bên nhau để giúp đỡ nhau, thay vì để những áp lực đó làm ảnh hưởng đến chúng ta. Em luôn có anh ở đây, sẵn sàng hỗ trợ khi em cần.

Cảm ơn em vì đã đọc những dòng này. Anh yêu em, rất nhiều.

", False, "right", ("Bradley Hand ITC", 40, "bold"))

    t.hideturtle()
    turtle.done()
else:
    print("Mật khẩu sai. Không thể mở khóa.")
