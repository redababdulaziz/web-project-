
<!DOCTYPE html>
<html lang="eng" dir="ltr" > 
<head> <title> pname </title> </head> 
<body>

    <h3>Home</h3>
    <h3>Artists</h3>
 <form action="action_page.php" method="post">
  <div class="container">
    <h3>Sign Up</h3>
    <p>Please fill in this form to create an account.</p>
    <hr>
    <label for="uname"><b>Username </b></label>
    <input type="text" placeholder="Enter Name" name="uname" required> <br>

    <label for="email"><b>Email</b></label>
    <input type="email" placeholder="youremeail@example.com" name="email" required> <br>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required> <br>

    <label for="psw-repeat"><b>Repeat Password</b></label>
    <input type="password" placeholder="Repeat Password" name="psw-repeat" required> <br>

    <p>By creating an account you agree to our <a href="#" style="color:dodgerblue">Terms & Privacy</a>.</p>

    <div class="clearfix">
      <button type="button" class="cancelbtn">Cancel</button>
      <button type="submit" class="signupbtn">Sign Up</button>
    </div>
  </div>
  </form>
<form action="action_page.php" method="post">
 <div class="container">
    <h3>Sign In</h3>
    <label for="uname"><b>Username</b></label>
    <input type="text" placeholder="Enter Username Or Email" name="uname" required> <br>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required> <br>

    <button type="submit">Login</button> </div>
    <span class="psw">Forgot <a href="#" style="color:dodgerblue">password?</a></span>

</form>

    <div class="footer_row">

        <div class="col-lg-2  col-md-3 col-xs-6">
            <div class="footer__link-area">
                <h4 class="footer__link-area__title">Tutorials</h4>

                <ul class="footer__links">
                    <li class="footer__links__nodes"><a class="link-node" href="/python-programming/examples" title="Python Examples">Python Examples</a></li>
                    <li class="footer__links__nodes"><a class="link-node" href="/javascript/examples" title="JavaScript Examples">JavaScript Examples</a></li>
                    <li class="footer__links__nodes"><a class="link-node" href="/c-programming/examples" title="C Examples">C Examples</a></li>
                    <li class="footer__links__nodes"><a class="link-node" href="/java-programming/examples" title="Java Examples">Java Examples</a></li>
                    <li class="footer__links__nodes"><a class="link-node" href="/kotlin-programming/examples" title="Kotlin Examples">Kotlin Examples</a></li>
                    <li class="footer__links__nodes"><a class="link-node" href="/cpp-programming/examples" title="C++ Examples">C++ Examples</a></li>
                </ul>
            </div>
        </div>

        <div class="col-lg-2 col-md-3 col-xs-6">
            <div class="footer__link-area">
                <h4 class="footer__link-area__title">Company</h4>

                <ul class="footer__links">
                    <li class="footer__links__nodes"><a class="link-node" href="/about-us" title="About us">About us</a></li>
					<li class="footer__links__nodes"><a class="link-node" href="/contact" title="Contact us">Contact</a></li>
				</ul>
            </div>
        </div>
		
        <div class="social-icons">
		    <div class="footer__link-area">
		        <h4 class="footer__link-area__title">social media</h4>
		        <ul>
		        <li class="footer__links__nodes"><a class="link-node" href="/" title="twitter">twitter</a></li>		
			    <li class="footer__links__nodes"><a class="link-node" href="/" title="insta">insta</a></li>

		        </ul>
			</div>
		</div>		
    </div>
	
	
 </body> 
 </html>
