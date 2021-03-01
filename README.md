## Hi, I'm Hardik 👋🏾 😎 
## A Blockchain & Frontend Developer 💻 

🔭 I'm currently building game on Flow Blockchian, it's a new blockchain built to power next-gen games, apps and the developers who build them.

🌱 I’m also learning about consensus algorithm to implement PoW, PoS and more about Defi!

👨‍💻 I love Reactjs, and I'm also learning Vue!

💪 I'm getting ready to release an dapp, stay tuned!

## I love building products and sharing knowledge. Want to get in touch 🌎:
<ul>
  <li><a href="mailto: er.hardiksharma05@gmail.com" style="text-decoration:none" target="_blank">Shoot me an Email<a/></li>
  <li><a href="https://www.linkedin.com/in/hardik-sharma/" style="text-decoration:none" target="_blank">Add me on LinkedIn</a></li>
  <li><a href="https://telegram.me/Oxhardik" style="text-decoration:none" target="_blank">Ping me on Telegram</a></li>
</ul>

<canvas id="myChart" width="400" height="400"></canvas>
<script>
var ctx = document.getElementById('myChart').getContext('2d');
var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
        datasets: [{
            label: '# of Votes',
            data: [12, 19, 3, 5, 2, 3],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
});
</script>



