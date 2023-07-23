# MappingPractice
Frameworks and language used - Java, SpringBoot, JPA, MYSQL database, Swagger UI

Data Flow
1. Controller (API)
   - AddressController [getAllAddress(), addAddress(), updateAddress(), deleteAddress()]
   - BookController [getAllBook(), addBook(), updateBookPrice(), deleteBook()]
   - CourseController [getAllCourse(), addCourse(), updateCourse(), deleteCourse()]
   - LaptopController [getAllLaptop(), addLaptop(), updateLaptop(), deleteLaptop()]
   - StudentController [getAllStudent(), addStudent(), updateStudent(), deleteStudent()]
2. Service
   - AddressService [getAllAddress(), addAddress(), updateAddressState(), deleteAddress()]
   - BookService [getAllBook(), addBook(), updateBookPrice(), deleteBook()]
   - CourseService [getAllCourse(), addCourse(), updateCourse(), deleteCourse()]
   - LaptopService [getAllLaptop(), addLaptop(), updateLaptop(), deleteLaptop()]
   - StudentService [getAllStudent(), addStudent(), updateStudent(), deleteStudent()]
3. Model
   Address(), Book(), Course(), Laptop(), Student()
4. Repository
   IAddressRepo(), IBookRepo(), ICourseRepo(), ILaptopRepo(), IStudentRepo()

Data Structure Used - MYSQL Database

Project Summary
This assignment is a complete revision on mapping as it has one-to-one, one-to-many, many-to-one, and many-to-many mappings.
