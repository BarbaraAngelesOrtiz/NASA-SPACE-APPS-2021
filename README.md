# NASA-SPACE-APPS-2021
We are Space Collector, a multidisciplinary group of students and professionals gathered with the shared goal of expanding access to research and spatial information for the community in general.


[LINK TO PROJECT DEMO](https://www.youtube.com/watch?v=8-dnytkb2to)

![image](https://user-images.githubusercontent.com/105976212/189555601-9ea92638-697f-4122-9756-6e31176b6997.png)

[LINK TO FINAL PROJECT](https://www.youtube.com/watch?v=Vh0RJ9X_AQM)


## BACKEND

### 1) BRIEF AEROSPACE PHYSICAL THEORY ⭐
A two-line element set (TLE) is a data format encoding a list of orbital elements of an Earth-orbiting object for a given point in time, the epoch. Using a suitable prediction formula, the state (position and velocity) at any point in the past or future can be estimated to some accuracy.

The TLE data representation is specific to the simplified perturbations models (SGP, SGP4, SDP4, SGP8 and SDP8), so any algorithm using a TLE as a data source must implement one of the SGP models to correctly compute the state at a time of interest.

The TLE format is a de facto standard for distribution of an Earth-orbiting object's orbital elements.

### 2) IMPLEMENTATION ✅
We use Orbit Predictor: is a Python library to propagate orbits of Earth-orbiting objects (satellites, ISS, FENGYUN-1C, etc) using TLE (Two-Line Elements set), based on the SGP4 implementation.

The following spatial tests were analyzed: FENGYUN-1C, COSMOS-970, RUBIN-8 & PSLV R / B, RUBIN-4 & SL-8 R / B, MICROSAT-R DEB and ISS. The input .tle files were pulled from Celestrak.

And as a result, we can determine for a given instant of time t:

Latitude, Longitude and Height.
Its position at that instant t.
Position, speed and mistake made.
Determine if it is possible to observe this object in our country.
All the results were applied to our country Argentina (ARG).

### 3) CODE 🙌
Just download this reposiory and run our main.ipynb.

### 4) RESULTS ANALYSIS FOR HUMANS🎯
#### 📡 4.1) FENGYUN-1C
When does sat on ARG happen again?

2021-10-03 22: 12: 22.855151
For the date analyzed: 10/02/2021 - Time: 00 hs: 00 min

Position: (-1064.0592394617108, 5464.299827067381, -4607.142057958034)
Speed: (2.3701221267458656, -4.246615675820121, -5.605410824794238)
Estimated error: None
Did this satellite pass through ARG at that moment? False

#### 📡 4.2) COSMOS-970
When does the sat happen again on ARG?

2021-10-03 14: 52: 52.039996
For the date analyzed: 10/02/2021 - Time: 00 hs: 00 min

Position: (-6081.133630702503, 4322.188936694305, 672.7760484793781)
Speed: (- 2.149751825250676, -2.128111442378591, -6.599542110075268)
Estimated error: None
Did this satellite pass through ARG at that moment? False

#### 📡 4.3) RUBIN-8 & PSLV R / B
When does the sat happen again on ARG?

2021-10-03 18: 49: 25.065949
For the date analyzed: 10/02/2021 - Time: 00 hrs: 00 min

Position: (4586.481163344431, 5016.5059094992175, 1629.9003537441338)
Speed: (1.9814251174607582, 0.5741439594696178, -7.277291551777174)
Estimated error: None
Did this satellite pass through ARG at that moment? False

#### 📡 4.4) RUBIN-4 & SL-8 R / B
When does the sat happen again on ARG?

2021-10-03 17: 01: 44.844248
For the date analyzed: 10/02/2021 - Time: 00 hrs: 00 min

Position: (-5717.817424965146, -4126.843135258802, -478.137351898629)
Speed: (-0.22524822450832388, 1.156089090332316, -7.412947661395255)
Estimated error: None
Did this satellite pass through ARG at that moment? False

#### 📡 4.5) MICROSAT-R DEB
When does the sat happen again on ARG?

2021-10-03 20: 34: 28.861189
For the date analyzed: 10/02/2021 - Time: 00 hs: 00 min

Position: (340.6305323284987, -6361.078537406675, -3643.0477158545386)
Speed: (-0.7226887162478327, -3.2645502875856685, 6.428455124184609)
Estimated error: None
Did this satellite pass through ARG at that moment? True

#### 📡 4.6) ISS
When does sat on ARG happen again?

2021-10-03 18: 24: 55.952657
For the date analyzed: 10/02/2021 - Time: 00 hs: 00 min

Position: (-6280.344678371433, -2218.522433242058, 616.5737715081176)
Speed: (1.0706020376146572, -4.723614689684127, -6.014517733596158)
Estimated error: None
Did this satellite pass through ARG at that moment? False

### Bibliography💬

[Celestrak](https://celestrak.org/)

[Satellogic](https://github.com/satellogic/orbit-predictor)

## FRONTEND

### 1) IMPLEMENTATION ✅

We use WorldWind: is an open source virtual globe API. WorldWind allows developers to quickly and easily create interactive visualizations of 3D globe, map and geographical information.

Because WorldWind is completely open source, extending the API is simple and easy to do.

### 2) CODE 🙌

If you do not already have a web server, you can use a minimal development web server built in Node.js:

[Download the Code](https://github.com/BarbaraAngelesOrtiz/NASA-SPACE-APPS-2021/files/9543862/Terminado1-20211004T005058Z-001.zip)

### 3) RESULTS ANALYSIS 🎯

![image](https://user-images.githubusercontent.com/105976212/189556094-8ca60169-fafe-4bf4-bb0b-b39d34ad07d9.png)

![image](https://user-images.githubusercontent.com/105976212/189556104-22240736-635f-478b-abaa-efb664ad6a7b.png)


### Bibliography💬

[World Wind NASA](https://worldwind.arc.nasa.gov/)

## Bussiness Model

![Canvas English](https://user-images.githubusercontent.com/105976212/189558019-5c3735b5-711f-4c23-9d4e-75a1670ae344.png)


