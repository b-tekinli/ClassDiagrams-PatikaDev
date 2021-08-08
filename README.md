# TASKS


## Task 1 - University Management Class Diagram

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Flag_of_Turkey.svg/1200px-Flag_of_Turkey.svg.png" width='61' height="auto">

Ödev - Üniversite Yönetim Sistemi <br />

- Üniversiteye ait sınıflıklar, çalışma ofisleri ve departmanlar vardır.
- Departmanlara ait ofisler vardır.
- Üniversiteye ait çalışanlar vardır. Bu çalışanlar profesör veya memur olabilir.
- Her çalışan bir ofiste çalışır.
Bu sistemi tasvir eden Class (Sınıf) diyagramını çiziniz.

Not : Sınıflara ait nitelik ve davranışların belirtilmesine gerek yoktur.


<br /> <br />


<img src="https://bewerbung.co/wp-content/uploads/2018/07/bewerbung-englisch.jpg" width='61'>

Homework - University Management System <br />

- There are classrooms, study offices and departments belonging to the university.
- There are offices belonging to the departments.
- It belongs to the university. It could be male or female.
- His employee is running in an office.
Draw the Class (Class) diagram describing this system.

Note: It is not necessary to specify the attributes and properties of the classes.

![UniversityManagementSystem](https://github.com/b-tekinli/PatikaDev-Task/blob/main/ClassDiagram/UniversityManagementSystem/UniversityManagementSystemClassDiagram.png)


<br /> <br />


## Task 2 - Zoo Management Class Diagram

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Flag_of_Turkey.svg/1200px-Flag_of_Turkey.svg.png" width='61' height="auto">

Ödev - Hayvanat Bahçesi <br />

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.

Hayvanlar:

- Atlar (atlar, zebralar, eşekler vb.),

- Kedigiller (kaplanlar, aslanlar vb.),

- Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.

- Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.

- Tür adı, ağırlığı, yaşı vb.

- Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()

- Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()

- Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.


<br /> <br />


<img src="https://bewerbung.co/wp-content/uploads/2018/07/bewerbung-englisch.jpg" width='61'>

Homework - Zoo Management System <br />

You design a system to track information about animals in a zoo.

Animals:

- Horses (horses, zebras, donkeys, etc.),

- Felines (tigers, lions, etc.),

- Characterized by species in groups such as rodents (rats, beavers, etc.).

- Most of the information stored about animals is the same for all groupings.

- Species name, weight, age, etc.

- The system should also be able to get the dosage of specific drugs for each animal => getDosage()

- System should be able to calculate Feed times => getFeedSchedule()

- The logic of the system to perform these functions will be different for each grouping. For example, the feeding algorithm will be different for horses and different for tigers.

Design a class diagram to handle the situation described above, using the polymorphism model.


![ZooManagementSystem](https://github.com/b-tekinli/PatikaDev-Task/blob/main/ClassDiagram/ZooManagement/ZooManagementClassDiagram.png)


<br /> <br />


## Task 3 - Flight Management System

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Flag_of_Turkey.svg/1200px-Flag_of_Turkey.svg.png" width='61' height="auto">

Ödev - Uçuş Yönetim Sistemi <br />

Uçuşların ve pilotların yönetimi için bir sistem tasarlayın.

- Hava yolu şirketleri uçuşları gerçekleştirir. Her hava yolunun bir kimliği vardır.

- Hava yolu şirketi, farklı tipteki uçaklara sahiptir.

- Uçaklar çalışır veya onarım durumunda olabilir.

- Her uçuşun benzersiz kimliği, kalkacağı ve ineceği havaalanı, kalkış ve iniş saatleri vardır.

- Her uçuşun bir pilotu ve yardımcı pilotu vardır ve uçağı kullanırlar.

- Havaalanlarının benzersiz kimlikleri ve isimleri vardır.

- Hava yolu şirketlerinin pilotları vardır ve her pilotun bir deneyim seviyesi mevcuttur.

- Bir uçak tipi, belirli sayıda pilota ihtiyaç duyabilir.

Bu sistemi tasvir eden Class(Sınıf) diyagramını çiziniz.


<br /> <br />


<img src="https://bewerbung.co/wp-content/uploads/2018/07/bewerbung-englisch.jpg" width='61'>

Homework - Flight Management System <br />

Design a system for the management of flights and pilots.

- Airline companies operate the flights. Every airline has an identity.

- The airline has different types of aircraft.

- Airplanes may be in working or repair condition.

- Each flight has a unique ID, airport to take off and land, departure and landing times.

- Every flight has a pilot and co-pilot, and they operate the plane.

- Airports have unique IDs and names.

- Airlines have pilots and each pilot has a level of experience.

- An aircraft type may need a certain number of pilots.

Draw the Class diagram describing this system.


![FlightManagementSystem](https://github.com/b-tekinli/PatikaDev-Task/blob/main/ClassDiagram/FlightManagementSystem/FlightManagementSystemClassDiagram.png)


<br /> <br />


## Task 4 - Online Movie System

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Flag_of_Turkey.svg/1200px-Flag_of_Turkey.svg.png" width='61' height="auto">

Ödev - Online Film Sitesi <br />

Online film satan veya kiralayan uygulamanın sistemini tasarlayın.

- Uygulamada filmler listelenebilir, sıralanabilir ve kullanıcılar uygulamaya abone olabilir.

- Kullanıcılar abonelik için sistem üzerinden kredi satın alır.

- Sadece abone olan kullanıcılar, kredileri ile film kiralayabilir ve kiraladığı filmin kredi bedeli kadar hesabından düşülür.

- Normal kullanıcılar ve aboneler film satın alabilirler.

- Eğer film mevcut değil ise talep edilebilir.

Bu sistemi tasvir eden Class(Sınıf) diyagramını çiziniz.


<br /> <br />


<img src="https://bewerbung.co/wp-content/uploads/2018/07/bewerbung-englisch.jpg" width='61'>

Homework - Online Movie Site <br />

Design the system of the application that sells or rents movies online.

- Movies can be listed and sorted in the app and users can subscribe to the app.

- Users purchase credits through the system for subscription.

- Only subscribed users can rent movies with their credits and the credit amount of the rented movie is deducted from their account.

- Regular users and subscribers can purchase movies.

- If the movie is not available, it can be requested.

Draw the Class diagram describing this system. 


![OnlineMovieSystem](https://github.com/b-tekinli/PatikaDev-Task/blob/main/ClassDiagram/OnlineMovieSystem/OnlineMovieSystemClassDiagram.png)


<br /> <br />


## Task 5 - Elevator Simulation

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Flag_of_Turkey.svg/1200px-Flag_of_Turkey.svg.png" width='61' height="auto">
<img src="https://bewerbung.co/wp-content/uploads/2018/07/bewerbung-englisch.jpg" width='61'>

![ElevatorSimulation](https://github.com/b-tekinli/PatikaDev-Task/blob/main/ClassDiagram/ElevatorSimulation/ElevatorSimulationSystemClassDiagram.png)
