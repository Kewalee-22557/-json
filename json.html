<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW" crossorigin="anonymous"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</head>
<body>
    <div class="container">  
        
        <div id="divInfo" class="row">
            <div class="col-12">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Molestiae suscipit esse magni porro asperiores possimus. Minima impedit quas qui non, nobis, nisi iure ex sed excepturi vel officiis in tenetur. 
                
          <p><button>back</button></p>
              
            
            </div>
        </div>
        

   
    <div id="divMain" class="row">
        <div class="col-12">  
            <span id="demo1">

            </span>
            <span id="demo2">

            </span>
        <table class="table" >
            <thead>
            <tr>
                    <th></th>
                    <th>ID</th>
                    <th>Title</th>
                    <th>Body</th>
                   
            </tr>
        </thead> <h1>Posts</h1>
        <tbody id="tblData">  </tbody>           
        </table>              
        </div>
    </div> 
</div>
         <div class="container">
            <p><span id="id"></span></p>
            <p><span id="title"></span></p>
            <p><span id="body"></span></p>
            </div>
                
    
    <script>

        function btnDele_click(id){
            //alert(id)
            $("#divInfo").show();
            $("#divMain").hide(); 
            var url = "https://jsonplaceholder.typicode.com/posts"+id;
            $.getJSON(url)
            .done((data)=>{
                $("#demo1").text( JSON.stringify(data));

                var url2 = "https://jsonplaceholder.typicode.com/posts"+id+"/comment";
                $.getJSON(url2)
                .done((data)=>{
                    $("#demo2").text( JSON.stringify(data));
                })
                .fail((xhr, status, error)=>{

                });
            })
            .fail((xhr, status, error)=>{

            });
        }

        function loadJSONArray(){
            var url = "https://jsonplaceholder.typicode.com/posts";
            $.getJSON(url)
                .done((data)=>{
                    console.log(data)
                    $.each(data, (k, item)=>{
                        console.log(item)
                        var line = "<tr>"
                            +"<td><button onClick='btnDele_click("+ item.id +")' "
                                +" class = 'btn-sm btn-primary'> i </button></td>"
                            +"<td>"+ item.id +"</td>"
                            +"<td>"+ item.title +"</td>"
                            +"<td>"+ item.body +"</td>"
                            +"</tr>";
                        $("#tblData").append(line);                           
                    });
                })
                .fail((xhr, status, err)=>{
                    console.log("error")
                })
        }
        $(()=>{
            $(()=>{
                $("#divInfo").hide();
            })
            loadJSONArray();
        });

    </script>

</body>
</html>