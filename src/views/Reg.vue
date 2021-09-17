<template>
 <section>
        <div>
            <div class="container">

                <form class="form-group">
                    <h1 class="text-center">Airline Booking Form</h1>

                    <div id="form">
                        <h4 class="text-white">Booking Details</h4>

                        <div id="input">
                            <input type="text" id="input-group" placeholder="From">
                            <input type="text" id="input-group" class="ms-3" placeholder="To">
                            <input type="text" id="input-group" placeholder="Departure Date">
                            <input type="text" id="input-group" class="ms-3" placeholder="Departure Time">
                            <select id="input-group" style="background: black;">
                                <option value="">Preffered Airline</option>
                                <option value="">IndoGo</option>
                                <option value="">AirIndia</option>
                                <option value="">SpaceJet</option>
                            </select>
                            <select id="input-group" style="background: black;" class="ms-3">
                                <option value="">Preffered Seating</option>
                                <option value="">Economy Class</option>
                                <option value="">Business Class</option>
                                <option value="">First Class</option>
                            </select>
                        </div>

                        <div id="input2">
                            <input type="number" id="input-group" placeholder="Adult">
                            <input type="number" id="input-group" placeholder="Children(2-11years)">
                            <input type="number" id="input-group" placeholder="infant(under 2years)">
                        </div>

                        <div id="input3">
                            <span id="input-group" class="text-primary">Select Your Fare</span>
                            <input type="radio" id="input-group" name="r">
                            <label class="text-white" for="input-group">One Way</label>
                            <input type="radio" id="input-group" name="r">
                            <label class="text-white" for="input-group">Round Trip</label>
                        </div>

                        <div id="input4">
                            <input type="text" id="input-group" placeholder="Return Date">
                            <input type="text" id="input-group" class="ms-3" placeholder="Return time">
                            <input type="text" id="input-group1" placeholder="Any Message">
                        </div>

                        <div id="input5">
                            <h4 class="text-white">Personal Details</h4>
                        </div>

                        <div id="input6">
                            <input type="text" id="input-group" placeholder="Full Nmae">
                            <input type="number" id="input-group" class="ms-3" placeholder="Phone Number">
                            <input type="email" id="input-group1" placeholder="Email">
                        </div>
                        <div class="mt-3">
                            <button type="submit" class="btn btn-success text-white">Submit</button>
                            <button type="reset" class="btn btn-danger ms-3">Cancel</button>
                        </div>
                    </div>

                </form>

            </div>
        </div>
    </section>     
</template>

<script>
export default {
   name:'Reg',
}
</script>

<style>
#form {
    background-color: #000;
    height: fit-content;
    width: 700px;
    margin: auto;
    padding: 20px;
    opacity: 0.7;
  }
  #form h4 {
    border-bottom: 2px solid #3399ff;
    width: 210px;
    padding: 5px;
  }
  ::placeholder {
    color: #fff;
  }
  #input #input-group {
    width: 300px;
    margin: 5px;
    border-top: none;
    border-left: none;
    border-right: none;
    outline: none;
    background: transparent;
    color: #fff;
  }
  #input2 #input-group {
    width: 195px;
    margin: 5px;
    border-top: none;
    border-left: none;
    border-right: none;
    outline: none;
    background: transparent;
    color: #fff;
  }
  #input3 #input-group {
    margin-left: 50px;
  }
  #input4 #input-group {
    width: 300px;
    margin: 5px;
    border-top: none;
    border-left: none;
    border-right: none;
    outline: none;
    background: transparent;
    color: #fff;
  }
  #input4 #input-group1 {
    width: 615px;
    margin: 5px;
    border-top: none;
    border-left: none;
    border-right: none;
    outline: none;
    background: transparent;
    color: #fff;
  }
  #input5 h4 {
    border-bottom: 2px solid #3399ff;
    width: 220px;
    padding: 5px;
  }
  #input6 #input-group {
    width: 300px;
    margin: 5px;
    border-top: none;
    border-left: none;
    border-right: none;
    outline: none;
    background: transparent;
    color: #fff;
  }
  #input6 #input-group1 {
    width: 615px;
    margin: 5px;
    border-top: none;
    border-left: none;
    border-right: none;
    outline: none;
    background: transparent;
    color: #fff;
  }
  /*media query*/
  @media (min-width: 340px) and (max-width: 460px) {
    #form {
        height: fit-content;
        width:400px;
        
    }
    #input #input-group {
        width: 160px;
    } 
    #input2 #input-group {
        width: 105px;
    }   
    #input3 #input-group {
        margin-left: 10px;
      }    
      #input4 #input-group {
        width: 160px;
      }
      #input4 #input-group1 {
        width: 350px;
      }
      #input6 #input-group {
        width: 160px;    
    }
    #input6 #input-group1 {
        width: 350px;
    }    
    
  }
</style>