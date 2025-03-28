<!DOCTYPE html>
<html>
<head>
    <title>위치 확인</title>
</head>
<body>
    <button onclick="getLocation()">내 위치 확인</button>
    <p id="location"></p>

    <script>
        function getLocation() {
            if (navigator.geolocation) {
                navigator.geolocation.getCurrentPosition(showPosition);
            } else {
                document.getElementById("location").innerHTML = "위치 정보를 사용할 수 없습니다.";
            }
        }

        function showPosition(position) {
            document.getElementById("location").innerHTML = 
                "위도: " + position.coords.latitude + "<br>경도: " + position.coords.longitude;
        }
    </script>
</body>
</html>
