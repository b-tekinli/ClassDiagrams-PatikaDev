# TASKS

### CLASS-DIAGRAMS
- [Task 1 - 📚 University Management Class Diagram](https://github.com/b-tekinli/PatikaDev-Task/tree/main/ClassDiagram/UniversityManagementSystem)
- [Task 2 - 🐶 Zoo Management Class Diagram](https://github.com/b-tekinli/PatikaDev-Task/tree/main/ClassDiagram/ZooManagement)
- [Task 3 - ✈️ Flight Management System](https://github.com/b-tekinli/PatikaDev-Task/tree/main/ClassDiagram/FlightManagementSystem)
- [Task 4 - 🎥 Online Movie System](https://github.com/b-tekinli/PatikaDev-Task/tree/main/ClassDiagram/OnlineMovieSystem)
- [Task 5 - 🏢 Elevator Simulation](https://github.com/b-tekinli/PatikaDev-Task/tree/main/ClassDiagram/ElevatorSimulation)

<details>
 <summary>:zap: CLASS DIAGRAMS </summary>

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

<br />

![UniversityManagementSystem](https://github.com/b-tekinli/PatikaDev-Task/blob/main/ClassDiagram/UniversityManagementSystem/UniversityManagementSystemClassDiagram.png)
    
<br />

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

<br />

![ZooManagementSystem](https://github.com/b-tekinli/PatikaDev-Task/blob/main/ClassDiagram/ZooManagement/ZooManagementClassDiagram.png)
      
      
 <br />


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

<br />

![FlightManagementSystem](https://github.com/b-tekinli/PatikaDev-Task/blob/main/ClassDiagram/FlightManagementSystem/FlightManagementSystemClassDiagram.png)


<br />


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


<br />


<img src="https://bewerbung.co/wp-content/uploads/2018/07/bewerbung-englisch.jpg" width='61'>

Homework - Online Movie Site <br />

Design the system of the application that sells or rents movies online.

- Movies can be listed and sorted in the app and users can subscribe to the app.

- Users purchase credits through the system for subscription.

- Only subscribed users can rent movies with their credits and the credit amount of the rented movie is deducted from their account.

- Regular users and subscribers can purchase movies.

- If the movie is not available, it can be requested.

Draw the Class diagram describing this system. 

<br />

![OnlineMovieSystem](https://github.com/b-tekinli/PatikaDev-Task/blob/main/ClassDiagram/OnlineMovieSystem/OnlineMovieSystemClassDiagram.png)


<br />


## Task 5 - Elevator Simulation

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Flag_of_Turkey.svg/1200px-Flag_of_Turkey.svg.png" width='61' height="auto">

Ödev - Asansör Simülasyonu <br />

Aşağıdaki problem ifadesine göre bir sınıf diyagramı tasarlayın. Nesne Yönelimli Programlamanın ilkelerini ve sınıflar arası ilişki durumlarını kullanmaya çalışın. (Encapsulation, Inheritance, Polymorphism, Abstraction)

- Kodluyoruz Sigorta Şirketi 12 katlı bir ofis binası inşa etmek ve onu en son asansör teknolojisi ile donatmak istiyor. Şirket, bina içindeki trafik akışı ihtiyaçlarını karşılayıp karşılamayacaklarını görmek için binanın asansörlerinin işlemlerini modelleyen bir yazılım simülatörü oluşturmanızı istiyor.

- Binada, her biri binanın 12 katına çıkabilecek beş asansör bulunacaktır. Her asansörün yaklaşık altı yetişkin yolcu kapasitesi vardır. Asansörler enerji tasarruflu olacak şekilde tasarlanmıştır, bu nedenle yalnızca gerektiğinde hareket ederler. Her asansörün kendi kapısı, kat gösterge ışığı ve kontrol paneli vardır. Kontrol panelinde hedef düğmeleri, kapı açma ve kapama düğmeleri ve bir acil durum sinyal düğmesi bulunur.

- Binadaki her katta, beş asansör boşluğunun her biri için bir kapı ve her kapı için bir varış zili vardır. Varış zili, asansörlerin bir kata vardığını gösterir. Her kapının üzerinde bulunan bir sinyal ışığı, asansörün gelişini ve asansörün hareket ettiği yönü gösterir. Her katta ayrıca üç set asansör çağrı düğmesi vardır.

- Bir kişi uygun çağrı düğmesine (yukarı veya aşağı) basarak bir asansörü çağırır. Bir programlayıcı, aramanın başladığı kata gitmek için beş asansörden birini görevlendirir. Asansöre girdikten sonra, bir yolcu tipik olarak bir veya daha fazla hedef düğmesine basar. Asansör kattan kata hareket ederken, asansörün içindeki bir gösterge ışığı yolcuları asansörün konumu hakkında bilgilendirir. Bir asansörün bir kata varması, dış asansör kapısının üzerindeki gösterge lambasının yakılması ve kat zilinin çalmasıyla belirtilir. Bir asansör bir katta durduğunda, her iki kapı grubu da önceden belirlenmiş bir süre boyunca otomatik olarak açılarak yolcuların asansöre girip çıkmalarına izin verir.

- Simülatör, gerçek zaman geçişini simüle etmek ve simülasyonda meydana gelen olayları zaman damgası ve günlüğe kaydetmek için bir "saat" kullanır. Simülatör tarafından yolcu oluşturmak ve her yolcu için kalkış ve varış katlarını belirlemek için rastgele bir sayı üreteci kullanılır.

<br /> <br />

<img src="https://bewerbung.co/wp-content/uploads/2018/07/bewerbung-englisch.jpg" width='61'>

Homework - Elevator Simulation <br />

Design a class diagram based on the following problem statement. Try to use the principles of Object Oriented Programming and relations between classes. (Encapsulation, Inheritance, Polymorphism, Abstraction)

- We Code The Insurance Company wants to build a 12-storey office building and equip it with the latest elevator technology. The company wants you to create a software simulator that models the operations of the building's elevators to see if they can meet the traffic flow needs within the building.

- The building will have five elevators, each of which can go up to 12 floors of the building. Each elevator has a capacity of approximately six adult passengers. Elevators are designed to be energy efficient, so they only move when needed. Each elevator has its own door, floor indicator light and control panel. The control panel has target buttons, door open and close buttons, and an emergency signal button.

- Each floor in the building has a door for each of the five elevator shafts and an arrival bell for each door. The arrival bell indicates that the elevators have arrived at a floor. A signal light on each door indicates the arrival of the elevator and the direction the elevator is moving. Each floor also has three sets of elevator call buttons.

- A person calls an elevator by pressing the appropriate call button (up or down). A scheduler assigns one of five elevators to go to the floor where the search started. Upon entering the elevator, a passenger typically presses one or more destination buttons. As the elevator moves from floor to floor, an indicator light inside the elevator informs passengers about the location of the elevator. The arrival of an elevator to a floor is indicated by the lighting of the indicator lamp above the outer elevator door and the ringing of the floor bell. When an elevator stops at a floor, both sets of doors open automatically for a predetermined time, allowing passengers to enter and exit the elevator.

- The simulator uses a "clock" to simulate real time lapse and timestamp and log events that occur in the simulation. A random number generator is used by the simulator to generate passengers and determine the departure and arrival floors for each passenger. 

<br />

![ElevatorSimulation](https://github.com/b-tekinli/PatikaDev-Task/blob/main/ClassDiagram/ElevatorSimulation/ElevatorSimulationSystemClassDiagram.png)

</details>
