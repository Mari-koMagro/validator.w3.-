1. შეცდომა : 
<head>
    <title>My Favorite Place</title>
    <meta charset="UTF-8"

meta-ს ჭირდება ">" მე-4 line-ში, სწორი ვერსია:
<head>
    <title>My Favorite Place</title>
    <meta charset="UTF-8">

2. img თეგს ჭირდება alt.

  <img
                src="images/place.jpg"
                width="500"
                height="300"
            >
სწორი იქნება : 

 <img
                src="images/place.jpg" alt="ადგილი"
                width="500"
                height="300"
            >

3. არასწორია : article თეგის დახურვამდე img-საც ჭირდება ">" დახურვა 

<article>

                <h3>First Place</h3>

                <p>
                    This is a very beautiful place to visit.
                </p>

                <img src="images/place1.jpg" alt="Beautiful place"

            </article>

სწორი იქნებოდა : 

<article>

                <h3>First Place</h3>

                <p>
                    This is a very beautiful place to visit.
                </p>

                <img src="images/place1.jpg" alt="Beautiful place">

            </article>

4.        არასწორია : 

 <table border="1">

 სწორია : 

  <table>



5. არასწორია : 
<!DOCTYPE html>
<html>

სწორია : 

<!DOCTYPE html>
<html lang="ka">


