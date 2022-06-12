# hukum_archimedes

## 
onCollide:
(e)=>{
    e.other.materialname == "telur" ? {
        e.other.density = 0.9;
        timeToLive = 0.1
    } : {}
}

Nilai density garam 1 adalah 0.9
Nilai density garam 2 adalah 0.65
