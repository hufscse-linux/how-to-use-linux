# Exercises

아래 명령어들을 테스트해본다.

## cat + redirection(>)

    $ cat > queen_of_california
	"Queen Of California"
	
    Goodbye cold, goodbye rain
    Goodbye sorrow, goodbye shame
    I'm headed out west with my headphones on
    Boarded a flight with a song in the back of my soul
    And no one knows

    I just found out her ghost left town
    The Queen of California is stepping down, down

    Hello beauty, hello strange
    Hello wonder, what's your name?
    Looking for the sun that Neil Young hung
    After the gold rush of 1971

    I just found out her ghost left town
    The Queen of California is stepping down, down

    [INSTRUMENTAL]

    If you see her say, "Hello"
    Just don't tell me, "I told you so"
    Joni wrote Blue in her house by the sea
    I gotta believe there’s another color waiting on me
    To set me free
    
    I just found out her ghost left town
    The Queen of California is stepping down, down

    [INSTRUMENTAL]

다 입력하고, Ctrl-x를 누르면 다시 Shell을 얻을 수 있다.

    $ ls -alh
	$ cat queen_of_california

## cat + redirection(>>)

    $ cat >> queen_of_california
	[END]
	$ cat queens_of_california

## cat + redirection(<)

    $ less < queens_of_california
	$ cat > file < queens_of_california


## Standard Output to File

    $ ps aux > ps_aux_output
    $ ps aux > ps_aux_output

## Standard Error Redirection

아래 두 명령의 차이를 비교해보자

    $ find / -name lib*
	$ find / -name lib* 2>/dev/null
