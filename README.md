<!DOCTYPE html><html>
<head>
<title>BharatGaav Connect</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body{font-family:Arial;background:#f5f5f5}
.card{background:white;padding:10px;margin:10px;border-radius:8px}
input,button{margin:5px;padding:8px;width:90%}
button{background:green;color:white}
</style>
</head><body><h2>BharatGaav Connect 🇮🇳</h2><h3>Add Service</h3><input id="name" placeholder="Name">
<input id="service" placeholder="Service">
<input id="phone" placeholder="Phone">
<input id="village" placeholder="Village"><button onclick="add()">Submit</button>

<h3>Services</h3>
<div id="list"></div><script>
let data = JSON.parse(localStorage.getItem("services")) || [];

function add(){
  let s = {
    name:name.value,
    service:service.value,
    phone:phone.value,
    village:village.value
  };

  data.push(s);
  localStorage.setItem("services", JSON.stringify(data));
  show();
}

function show(){
  list.innerHTML="";
  data.forEach(s=>{
    list.innerHTML += `<div class="card">
      <b>${s.service}</b><br>
      ${s.name}<br>
      📍 ${s.village}<br>
      📞 ${s.phone}
    </div>`;
  });
}

show();
</script></body>
</html>
