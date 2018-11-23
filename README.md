# VISTA PHP USER Defined Function Libery Developed by Guddu Modok.
.....................................................................................................................................
# First download the zip file.than extract it into root folder.than include vista/.vista
# or Use VISTA CDN https://vcsites.xyz/vista/.vista


---------------------------------------------------------------------------------------------------------------------------------------
1. redirect(target link); :-Redirect to the Target Location

2. timeredirect(time,target link);:-Redirect you to the target link when the time is up.
                                    example~ timeredirect("0-s","www.vcsites.xyz");
          This Function help you to redirect you when the page load then 0 second up then you redirect you in www.vcsites.xyz.Here You can           0-s mean 0 second,0-m mean 0 minute,0-h mean 0 hours.
          
3. p("anything");:- Display any output.Its also help you to display array or objects.

4. en("value");:-break lines how much you enter your value.

5.sthead() ; :-start head tag .

6.ehead() ; :-End Head tag.

7.hideerror(); :-Hide all Error and warnings.

8.rightclick(); :-Start a Right Click option .

9.rc_menu("name","link"); :-Add menu option.

10.erightclick(); :-End Right Click Option.

11.input("type","name","placeholder/value"); :-Insert a input type.

12.select("name","option names"); :-insert a select type.

14.menu("type","menu lists"); :-Insert a menu option like order,unorder.

15.form("action"."method"); :-Open a form tag.

16.eform(); :-End Form tag.

17.speak("speak something"); :-Speaking text.

18.alert("hellow"); :-Alert something.

19.confirm("hellow world"); :-Confirm box

20.stuploadform("action","method") ; :-start a file uploadig form.

21.euploadform(); :-End uploadig form.

22.uploadfile("target_dir","size"); :-Upload a file.

23.d("/"); :-Date.

24.t(":"); :-Time

25.createfile("filename","content"); :-Create a File.

26.source("url"); :-source code.

27.cookie("Cookie name","value","day"); :-Create a Cookie.

28.displaycookie("Cookie name"); :-Display Cookie Value.

29.deletecookie("Cookie name"); :-Delete a Cookie.

30.clearall(); :-Clear All Cookies and Cache.

31.device("mobile URL ","pc URl "); :-Automatic Redirect the correct URl.If That is moile than system redirect in Mobile link else laptop link.

32.deletefile("filename"); :-Delete a File.

33.sttopnav(); :-Start a top nav bar.

34.href("url:title;url:title"); :-Insert Hyperlinks

35.stdropdown("Button name"); :-Insert a Drop Down Button.

36.edropdown(); :-End dropdown Button

37.etopnav(); :-End Topnav.

38.sum(10,20,30,50); :-Summation or Addition of Numbers.

39.h1("Text"); :-Insert a H1 tag

40.h2("Text"); :-Insert a H2 Tag

41.h3("Text"); :-Insert a H3 tag.

42.h4("Text"); :-Insert a H4 tag.

43.h5("Text"); :-Insert a H5 tag.

44.h6("Text"); :-Insert a H6 tag.

45.add("first","second"); :-Add anything.

46.upper("string"); :-Display uppercase.

47.lower("string"); :-Display Lowercase.

48.capi("string"); :-Display capitalize.

49.sup("string"); :-Display Super script

50.sub("string"); :-Display SubScript

51.post("tagname"); :-Return a form value of post method

52.get("tagname"); :-Return a form value of get method

53.mail_api("to email address","form","subject","message","return"); :-Send email.

54.block_f5(); :-Block F5 key.

55.namta("enter the value"); :-Display the table.

56.data("connection code","sql code","rows name"); :-Display data from Mysql.

57.seo("url","Tag name"); :-Get the value of any head tag of any url

58.extract_title("url"); :-Extract the title from a website.

59.find_all_href("URL"); :-Find all links from a URL.

60.fevicon("URL"); :-Get the Fevicon url from a URl.

61.html_tag_count("URL","tag name"); :-Count the Tag name from a url.

62.count_all_img("URL"); :-Count the All Image from url.

63.server("all"); :-Get Server Details.

64.jquery(); :-Include jquery.

65.createkeyboard("ID"); :-Create a New Keyboard into your website.Note:-Include in sthead() function.

66.keyboardstart("ID"); :-Now start to Keyboard options.Include it after ehead() function.

67.keyboard("ID","value"); :-Insert keyboard keys.

68.backkey("ID"); :-insert a Back key into your keyboard.

69.donekey("Id"); :-insert a Done Key into your Keyboard.

70.row_count("Connection code","mysql code"); :-Count the Total row from a table.

71.title("website title"); :-Website Title.Include after sthead() function.

72.keywords("webiste keywords"); :-Insert keywords.Include it after sthead() function.

73.mdes("Description"); :-insert meta description.Include it after sthead() function.

74.vibrate("time"); :-vibrating.
