 <!DOCTYPE html>
<html>
   <head>
       <title>Split Payment</title>

       <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    
    <link rel="stylesheet" type="text/css" media="screen" href="css/mine.css"/>
     <link rel="stylesheet" media="all" href="css/bootstrap.min.css" />
     <script src="https://api.ravepay.co/flwv3-pug/getpaidx/api/flwpbf-inline.js"></script>
   </head>
<body>
<div class="container">
    <div class="row ">
        <div class="col-md-8 col-lg-8 col-sm-8">
            <div class="card">
            <div class="card-header">
            <div class="card-subtitle">
                <h4 class="text-success">How Can FlutterWave Handle This?</h4>
                

                <h5>Flutterwave can solve this by using the Rave's split payment feature which 
allows you split a transaction between two (2) or more accounts and collect fees on the transaction.
Rave can automatically split the settlement such that the vendor's account is credited and the platform 
owner gets his own commission credited as well.</h5>
<center><h2>Click on the link below for the Demo</h2></center>
                <form >
                   
                    <div class="btn text-center">
                            <button type="button" onClick="payWithRave()" class="btn btn-primary">Pay Now</button>
                           
                    </div>
                </form>
            </div>
            </div>
            </div>

        </div>
    
    </div>
    </div>


     </body>
</html> 



 
<script>
    const API_publicKey = "FLWPUBK_TEST-a07005a7dff22ade0f0666ed94fa39f8-X";

    function payWithRave() {
        var x = getpaidSetup({
            PBFPubKey: API_publicKey,
            customer_email: "user@example.com",
            amount: 20000,
            currency: "NGN",
            txref: "rave-123456",
            subaccounts: [
              {
                id: "RS_D87A9EE339AE28BFA2AE86041C6DE70E",
		            transaction_split_ratio:"2",
                transaction_charge_type: "flat",
                transaction_charge: "100"
              },
              
              {
                id: "RS_344DD49DB5D471EF565C897ECD67CD95",
                transaction_split_ratio:"3",
                transaction_charge_type: "flat",
                transaction_charge: "100"
              },
              
              {
                id: "RS_839AC07C3450A65004A0E11B83E22CA9",
                transaction_split_ratio:"5",
                transaction_charge_type: "flat",
                transaction_charge: "100"
              }
            ],
            meta: [{
                metaname: "flightID",
                metavalue: "AP1234"
            }],
            onclose: function() {},
            callback: function(response) {
                var txref = response.tx.txRef; // collect flwRef returned and pass to a 					server page to complete status check.
                console.log("This is the response returned after a charge", response);
                if (
                    response.tx.chargeResponseCode == "00" ||
                    response.tx.chargeResponseCode == "0"
                ) {
                    // redirect to a success page
                } else {
                    // redirect to a failure page.
                }

                x.close(); // use this to close the modal immediately after payment.
            }
        });
    }
</script>