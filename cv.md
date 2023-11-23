# rsschool-cv

## Alem Bakhytzhanova

## Contact Information 
- Email: hstoreez@gmail.com
- Phone: + 7 701 505 05 00
- LinkedIn [Alem Bakhytzhanova](www.linkedin.com/in/alembb)
- GitHub: [Alem Bakhytzhanova](https://github.com/mirvision)

## Briefly About Myself:
 I'm a young programming enthusiast embarking on the exciting journey in the IT industry at the age of 25. Currently, I am actively learning programming with a focus on the Go (Golang) language. My primary goal is continuous enrichment of my skills and knowledge in programming. I aim to participate in exciting projects where I can apply my skills and contribute to the advancement of technology. I am characterized by a passion for learning, a creative approach to problem-solving, and a constant commitment to self-improvement. I am ready for new challenges and confident that my contributions can make a significant impact in the programming world.

I look forward to new opportunities and interesting projects where I can showcase myself as a skilled programmer and a valuable team member.


## Skills 
- Golang Language
- HTML5, CSS3
- Git, GitHub
- VS Code
- Windows OS, Linux(Ubuntu)

## Code Example
func StringToNumber(str string) int {
	var result int
	sign := 1

	runes := []rune(str)
	if runes[0] == '-' {
		runes[0] = '0'
		sign = -1
	}
	for _, ch := range runes {
		if ch >= '0' && ch <= '9' {
			result = result*10 + (int(ch - '0'))
		}
	}
	return result * sign
}

## Courses
- HTML and CSS Tutorials 
- Golang on the Stepik