# json-data shaqo
```s
{
  "diiwaanka": [
    {
      "sumadda": 100,
      "magaca": "Cali",
      "adreeska": "Hodan",
      "shaqada": "fuundi"
    },
    {
      "sumadda": 200,
      "magaca": "Cabdi",
      "adreeska": "Waabari",
      "shaqada": "faryaamo"
    },
    {
      "sumadda": 300,
      "magaca": "Yuusuf",
      "adreeska": "Wadajir",
      "shaqada": "makaanik"
    },
    {
      "sumadda": 400,
      "magaca": "Faadumo",
      "adreeska": "XamarWayne",
      "shaqada": "dahable"
    },
    {
      "sumadda": 500,
      "magaca": "Maryan",
      "adreeska": "HowlWadaag",
      "shaqada": "dukaanle"
    },
    {
      "sumadda": 600,
      "magaca": "muuse",
      "adreeska": "dharkeenleey",
      "shaqada": "kawaanle"
    },
    {
      "sumadda": 700,
      "magaca": "awees",
      "adreeska": "shingaani",
      "shaqada": "xarqaanle"
    },
    {
      "sumadda": 800,
      "magaca": "cadirashiid",
      "adreeska": "wardhiigleey",
      "shaqada": "dilaal"
    },
    {
      "sumadda": 900,
      "magaca": "xuseen",
      "adreeska": "kaaraan",
      "shaqada": "dhaqtar"
    },
  
    {
      "sumadda": 1000,
      "magaca": "daahir",
      "adreeska": "boondheere",
      "shaqada": "dabato"
    }
  ]
}



```

('http://jsonplaceholder.typicode.com/posts?_limit=10');

poweisheel-chache
.................
PS C:\Users\mohia> npm cache verify
Cache verified and compressed (~\AppData\Local\npm-cache\_cacache)
Content verified: 0 (0 bytes)
Index entries: 0
Finished in 0.017s
PS C:\Users\mohia>
..............
<!-- <p class="title">liiska-diiwaanka wuu shaqaynayaa!</p>

  
     
        
    
      <div class="container">
        <div  class="card">
          <div class="col-4">
            <form >
                <div class="mb-3 mt-3">
                    <label for="sumadda">sumadda</label>
                    <input type="test" class="form-control" id="name" placeholder="sumadda" name="summadda">
                  </div>
              
              <div class="mb-3">
                <label for="magaca">magaca</label>
                <input type="text" class="form-control" id="magaca" placeholder="magaca" name="magaca">
              </div>
    
              <div class="mb-3 mt-3">
                <label for="adreeska">adreeska</label>
                <input type="email" class="form-control" id="adreeska" placeholder="adreeska" name="adreeska">
              </div>
              <div class="mb-3 mt-3">
                <label for="shaqada">shaqada</label>
                <input type="text" class="form-control" id="shaqada" placeholder="shaqada" name="shaqada">
              </div>
              
              <button type="submit" class="btn btn-primary">kudarso-diiwaanka</button>
          <span class="delete-user">   <button type="submit" class="btn btn-warning m-3">kaTir-diiwaanka</button></span>
            </form>
          </div>
        </div>
    
      </div>
          
    

<div class="container">
  <div class="card">
    <div class="col-8">
     <table class="table table-hover">
        <thead>
          <th>Sumadda</th>
          <th>Magaca</th>
          <th>Adreeska</th>
          <th>SHaqada</th>
          
        </thead>
        <tbody>
          @for (item of items; track item.sumadda){
          <tr>
            <td>{{ item.sumadda}}</td>
            <td>{{ item.magaca}}</td>
            <td>{{ item.adreeska}}</td>
            <td>{{item.shaqada}}</td>
           }
        </tbody>
      </table> 
    </div>
  </div>
</div>
        
        
  


     -->

     
  <div class="row">
    <div class="col-8">
     <div class="card">
       <div class="card-header bg-secondary text-white">
        
   <div class="card-body">
    <div class="row">
     <div class="col-12">
   
       <table class="table table-hover">
     
         <thead>
   
           <th>Summadaa</th>
           <th>Magaca</th>
           <th>Adreeska</th>
           <th>Shaqada</th>
           
           
           
         </thead>

         
         <tbody>
           @for (item of items; track item.sumadda){
           <tr>
            <td>{{ item.sumadda}}</td>
            <td>{{ item.magaca}}</td>
            <td>{{ item.adreeska}}</td>
            <td>{{item.shaqada}}</td>
             <td>
            
             <td>
               <button class="btn btn-small btn-primary">kudar-Diiwaanka</button>
             </td>
             <td>
            
               <button class="btn btn-small  btn-warning" style="margin-left: 10px;">katir-Diiwaanka</button>
               
          
            
             </td>
            }
         </tbody>
       </table> 
     </div>
   
    </div>
   </div>
   
       </div>
   
     </div>
   
    </div>
    <div class="col-4">
     <div class="card">
       <div class="card-header bg-secondary text-white">
        <h5>Diiwaan Galin</h5>
   
       </div>
   <div class="card-body">
   <div class="row">
     <div class="col-4">
   <label for="">summadda</label>
   <input type="text" class="form-control">
     </div>
     <div class="col-8">
   <label for="">magaca</label>
   <input type="text" class="form-control">
     </div>
     <div class="col-12">
   <label for="">adreeska</label>
   <input type="text" class="form-control">
     </div>
     <div class="col-12">
   <label for="">shaqada</label>
   <input type="text" class="form-control">
     </div>
   
   </div>
   
   <div class="row pt-2">
     <div class="col-6 text-center">
   <button class="btn btn-secondary">tir-tir</button>
     </div>
   
     <div class="col-6 text-center">
       <button class="btn btn-secondary">xarayso</button>
     </div>
   
    </div>
   </div>
   
     </div>
   
    </div>
   
    
     </div>        
