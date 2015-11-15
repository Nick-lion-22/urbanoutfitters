<!DOCTYPE html>
<html>
<head>
    <title>Geocoding service</title>
    <script src="https://maps.googleapis.com/maps/api/js"></script>
    <meta name="viewport" content="initial-scale=1.0, user-scalable=no">
    <meta charset="utf-8">
</head>
<body>

    <table id="myTable" cellspacing="0" border="1">
        <tr>
            <td>id</td>
            <td>address</td>
            <td>country</td>
            <td>postal code</td>
            <td>latitude and longitude</td>
        </tr>
        </tbody>
    </table>

<script>
var zipcode= ['20004','94101'];// array value zipcode
zipcode.forEach(function(zip_address) {
    console.log(zip_address);
    var geocoder = new google.maps.Geocoder();
    geocodeAddress(geocoder , zip_address);
});
    function geocodeAddress(geocoder , address) {
        geocoder.geocode({'address': address}, function(results, status) {
            if (status === google.maps.GeocoderStatus.OK) {
                var mas_dani= [];
                var cordinats = results[0].geometry.location
                mas_dani[0]=results[0].place_id;   // get id zipcode
                mas_dani[1]=results[0].formatted_address;// get adress
                mas_dani[2]=results[0].address_components[3].long_name; // get country
                mas_dani[3]=results[0].address_components[0].long_name; // get postal code
                mas_dani[4]=results[0].geometry.location.lat() +','+ results[0].geometry.location.lng();//get
                if(mas_dani) {
                    addRow('myTable', mas_dani);
                }
            } else {
                alert('Geocode was not successful for the following reason: ' + status);
            }
        });
    }
        function addRow(id, mas_d){
            console.log(mas_d)
            console.log(mas_d[0])
//            alert(mas_d[0]);
            var tbody = document.getElementById(id).getElementsByTagName("TBODY")[0];
            var row = document.createElement("TR")
            var td1 = document.createElement("TD")
            td1.appendChild(document.createTextNode(mas_d[0]));
            var td2 = document.createElement("TD")
            td2.appendChild (document.createTextNode(mas_d[1]));
            var td3 = document.createElement("TD")
            td3.appendChild(document.createTextNode(mas_d[2]));
            var td4 = document.createElement("TD")
            td4.appendChild (document.createTextNode(mas_d[3]));
            var td5 = document.createElement("TD")
            td5.appendChild(document.createTextNode(mas_d[4]));
            row.appendChild(td1);
            row.appendChild(td2);
            row.appendChild(td3);
            row.appendChild(td4);
            row.appendChild(td5);
            tbody.appendChild(row);
        }//function print table java skript

</script>
</body>
</html>
