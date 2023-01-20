# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Clone the github repository into Theia IDE.

### Step 2:
Create a new Django project.

### Step 3:
Write the needed HTML code.

### Step 4:
Run the Django server and execute the HTML files.

## Code:
```python

map.html
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Chidhambaram City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Silambarasan(22008639)</b></font>
</h3>
<center>
<img src="/static/image/maps.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="20,20,10" href="/static/html/hospi.html" title="Skin hospital">
<area shape="circle" coords="700,300,30" href="/static/html/temp.html" title="Thillai Nataraja Temple">
<area shape="circle" coords="200,80,40" href="/static/html/hotel.html" title="Moorthy Cafe">
<area shape="circle" coords="325,400,10" href="/static/html/lgstores.html" title="LG Home Appliances Showroom">
<area shape="rectangle" coords="170,250,1,1" href="/static/html/bank.html" title="Karur Vysya Bank">
</map>
</center>
</body>
</html>

bank.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Karur Vysya Bank</title>
</head>
<body bgcolor="silver">
<h1 align="center">
<font color="red"><b>Chidhambaram City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Karur Vysya Bank</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
One such Bank - Karur Vysya Bank - was set up in Karur in 1916 by two great visionaries and illustrious sons of Karur, the Late Shri M A Venkatarama Chettiar and the Late Shri Athi Krishna Chettiar to provide financial support to the traders and agriculturists in and around Karur, a textile town in Tamil Nadu.Karur Vysya Bank is a privately held Indian bank headquartered in Karur in Tamil Nadu. The company operates in four business segments: treasury operations corporate/ wholesale banking operations retail banking operations and other banking operations.</font>
</p>
</body>
</html>

hospi.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Skin Hospital</title>
</head>
<body bgcolor="voilet">
<h1 align="center">
<font color="red"><b>Chidhambaram City</b></font>
</h1>
<h3 align="center">
<font color="white"><b>Skin Hospital</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
Ridhan Skin Hospital is best Hospital in Chidhambaram.It is one of the top rated hospital with advanced facilities , round the clock doctors availability, quality care and affordable surgical treatment packages. Ridhaan Hospital provides both emergency and elective services with efficient staff to provide the best quality care to the patient. Ridhaan Hospital has the amenities and facilities as Doctor Home Visit Facility,Drinking Water Facility,Near By ATM Counter,Waiting Lounges,WIFI Facility etc.</font>
</p>
</body>
</html>

hotel.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Moorthy Cafe</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Chidhambaram City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Moorthy Cafe</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
The History of Moorthy Cafe can be traced all the way back to 1955. Founded by Mr. S. Dhakshina Moorthy and Mrs. Nagavalli under the name of Moorthy Cafe Veg and Non-Veg Hotel, which over the years have become famous with its name and cooking style. It was first originated in North Main Road, Chidambaram.</font>
</p>
</body>
</html>

lgstores.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>LG Home Appliances Showroom</title>
</head>
<body bgcolor="brown">
<h1 align="center">
<font color="red"><b>Chidhambaram</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>LG Home Appliances Showroom</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
LG Electronics Inc. is a South Korean multinational electronics company headquartered in Yeouido-dong, Seoul, South Korea. LG Electronics is a part of LG Corporation, the fourth largest chaebol in South Korea, and often considered as the pinnacle of LG Corp with the group's chemical and battery division LG Chem.LG Electronics was established in 1958 and has since led the way into the advanced digital era thanks to the technological expertise acquired by manufacturing many home appliances such as radios and TVs</font>
</p>
</body>
</html>

temp.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Thillai Nataraja Temple</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Chidhambaram City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Thillai Nataraja Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
Thillai Nataraja Temple, also referred as the Chidambaram Nataraja Temple, is a Hindu temple dedicated to Nataraja, the form of Shiva as the lord of dance. This temple is located in Chidambaram, Tamil Nadu, India. This temple has ancient roots and a Shiva shrine existed at the site when the town was known as Thillai.Chidambaram, the name of the city literally means "stage of consciousness". The temple architecture symbolizes the connection between the arts and spirituality, creative activity and the divine. The temple wall carvings display all the 108 karanas from the Natya Shastra by Bharata Muni, and these postures form a foundation of Bharatanatyam, an Indian classical dance.</font>
</p>
</body>
</html>

```

## Output:
![output](Screenshots/bank.png)
![output](Screenshots/hospi.png)
![output](Screenshots/hotel.png)
![output](Screenshots/hotelmap.png)
![output](Screenshots/htmlvalidator.png)
![output](Screenshots/lgstores.png)
![output](Screenshots/temp.png)

## Result:
The program for implementing image map is executed successfully