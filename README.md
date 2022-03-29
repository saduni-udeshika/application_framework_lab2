Year 3 - 2022
SE3040 – Application Frameworks
Lab 02
Lab session 2 – JavaScript
Objective: Teach a set of basic concepts in the JavaScript programming language.
Prerequisites: Students should have basic JavaScript knowledge.
1. Promises/Asynchronous and callbacks
   • Create a function that returns a value after 1 second (return inside a setTimeout).
   • Pass a callback (function) to the function created in the previous step and execute that
   function inside the timeout by passing the value.
   • Now return a promise instead of accepting the callback.
   • Let’s try to chain these promises.
2. Classes in JavaScript
   • Create a class named Vehicle using a function.
   • Add a property named type to the class (this.type). Assign a value to that variable
   using a
   constructor argument.
   • Add a function to its prototype named drive (Vehicle.prototype.print...). Print
   ‘Vehicle is
   driving’ in the function body.
   • Add VehicleCount (Vehicle.VehicleCount) as a static variable.
   • Increase the number of VehicleCount (Vehicle.VehicleCount++) by one inside the
   constructor.
   • Create an object from Vehicle class (new Vehicle) and check static variable value,
   type
   property value and function work.
   • Create a class named Car and extend the class Vehicle (Car.prototype =
   Object.create(Vehicle.prototype); Car.prototype.constructor = Car).
   • Add a new method called balanceWheels to Car and print ‘Wheels are balanced’ in
   the
   function body.
   BSc (Hons) in Information Technology
   Specializing in Software Engineering
   Year 3 - 2022
   SE3040 – Application Frameworks
   Lab 02
   • Call balanceWheels and drive methods using a car object and verify the
   functionality.
   • Check the static variable value and type variable value. Notice that they are not
   correct.
   • The reason for the above behavior is that we didn’t call the parent constructor from
   the
   child class. Do this by using the call method (in Car constructor function
   Vehicle.call(this,
   type);)
   • Re-validate the values.
3. Use arrow functions.
4. Try exercise 1 with async/await.
5. Try exercise 2 class, extends, get, set, and super keywords.
6. Try out the following.
   • Create an account in one of the Git repositories (GitHub, GitLab).
   • Create a directory and make it Git managed.
   • Add a text file to the directory with some text.
   • Stage the file and commit the changes.
   • Create a remote repository corresponding to the directory.
   • Push the changes to the remote repository.
   • Try opening the file from the Git remote repository and do some changes.
   • Commit the changes to the remote repository.
   • Pull the changes to the local directory.
