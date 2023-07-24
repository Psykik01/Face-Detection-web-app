
![Face_Detection_Web-app](https://user-images.githubusercontent.com/67871111/130376276-731be056-3dd5-4b3d-b38b-ff2c23a86cd3.png)

    
## Face Recognition and Re-identification deployed using Flask
This is a face detection and re-identification web app.

At the time of creation of this project(08-2021,COVID-19 Pandemic) various places have restricted access only for people who are vaccinated.
Here's where this project can be a game changer.
We can identify people and cross reference their face with the database and tell you if they are vaccinated or not, with the help of only ONE PHOTO of the person.

Here I make use of the Face-recognition library to detect facial features and store them in an array along with its unique face ID.

While running the program I detect the faces present and cross reference these faces with the faces we stored in the array of known faces.

After identifying the faces we draw a green box around it if the person is vaccinated according to our database and a red box if he or she is not vaccinated according to our database.
If we don't have their face ID we assume they are not vaccinated and draw a red box around their face.






## Project Structure

![FileStruct2](https://user-images.githubusercontent.com/67871111/130378205-36a8735f-d8d0-49a1-a163-293b5b9b2a91.jpeg)

![FileStruct1](https://user-images.githubusercontent.com/67871111/130378131-3a9aea2b-1e6c-4658-a4db-98f8c2a7d81d.jpeg)  
## Deployment

To deploy this project run

```bash
  cd Flask face detection
```
```bash
  Ref1.py
```

  
## Demo
![gif1](https://user-images.githubusercontent.com/67871111/130377572-1e5370ec-0346-4991-a369-33706c3680fb.gif)


## Screenshots


![SS-](https://user-images.githubusercontent.com/67871111/130379917-a2b5994a-8b87-43fc-8368-8ca18b355f6a.jpg)


![SS-1](https://user-images.githubusercontent.com/67871111/130379839-d1d90ad8-c923-4c7b-9dd6-589396c465ac.jpg)




  
## Other Used Cases

This project is used by the following companies:

- Employees check in at office premises.

- Restricted access areas at a military bases.

- Airports.

  
## Documentation

[Documentation](https://linktodocumentation)

  
## Acknowledgements

 - [Face-recognition 1.3.0](https://pypi.org/project/face-recognition/)
 - [Flask](https://flask.palletsprojects.com/en/2.0.x/)
 - [Dlib](http://dlib.net/)

  