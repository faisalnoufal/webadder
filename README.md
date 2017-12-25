### webAdder


    <form class="container" action="https://formspree.io/faisalnoufal@gmail.com" method="post">
        <p class="h4 text-center mb-4">Write to us</p>

        <div class="md-form">
            <i class="fa fa-user prefix grey-text"></i>
            <input type="text" id="form3" class="form-control" name="Name">
            <label for="form3"></label>
        </div>

        <div class="md-form">
            <div class="row">
                <div class="col">
                    <i class="fa fa-envelope prefix grey-text"></i>
                    <input type="email" id="form2" class="form-control validate" name="_replyto">
                    <label for="form2"></label>
                </div>
                <div class="col">
                    <i class="fa fa-phone prefix grey-text"></i>
                    <input type="number" id="form32" class="form-control validate" name="Phone">
                    <label for="form34"></label>
                </div>
            </div>


            <div class="md-form">
                <i class="fa fa-pencil prefix grey-text"></i>
                <textarea type="text" id="form8" class="md-textarea" style="height: 100px" name="Message"></textarea>
                <label for="form8"></label>
            </div>
        </div>

        <div class="text-center">
            <!--        <input type="submit" value="Send">-->
            <button class="btn btn-unique">Send <i class="fa fa-paper-plane-o ml-1"></i></button>
        </div>


        <input type="hidden" name="_next" value="http://www.skiddydrive.com" />
        <input type="hidden" name="_subject" value="New lead from SkiddyDrive!" />
        
        <input type="hidden" name="_format" value="plain" />

    </form>

