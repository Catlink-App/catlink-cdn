         var currentTime = new Date()
         var hours = currentTime.getHours()
         var minutes = currentTime.getMinutes()
         if (minutes < 10){
          minutes = "0" + minutes
      }
        var t_str = hours + ":" + minutes + " ";
        if(hours > 11){
          t_str += "PM";
        } else {
          t_str += "AM";
      }

        function updateTime(){
            var currentTime = new Date()
            var hours = currentTime.getHours()
            var ampm = hours >= 12 ? 'PM' : 'AM';
            hours = hours % 12;
            hours = hours ? hours : 12; // the hour '0' should be '12'
           var minutes = currentTime.getMinutes()
            minutes = minutes < 10 ? '0'+minutes : minutes;

           var t_str = hours + ":" + minutes + " " + ampm;
            document.getElementById('sidetime').innerHTML = t_str;
        }
          setInterval(updateTime, 300);

                  
