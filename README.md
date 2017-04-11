# Build a fake API with JSON Server and API Testing with Jmeter

Here are the details to run the project:

1 . Setup the server:

* Requirements:
 - Check if NodeJS exists with command line : node -v. If not, please install it
 - Install JSon-Server with command line : install -g json-server
 - Check if JSon-Server is installed by command line : json-server
 - Install JDK and JMeter
 
2. Explanation :
 - JSon-Server works with only object-oriented syntax. That means you should have a JSON file like : 
   {
    “objects” :
      [
        {object1},
        {object2}
      ]
   }
To check if your JSON file is ok, go to this link : localhost:3000/objects. If everything is ok, you should see your API available.   
 
3. Run the test:
- Open JMeter and browse to the file with extension = .jmx
- Click run to see the result

You also could browse to this link : http://www.testing.vn/jmeter-tai-lieu-huong-dan-build-api-bang-json-server-va-test-api-su-dung-jmeter/

Happy testing !
