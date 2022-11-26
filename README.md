```javascript
import skitz from 'skitzcod4'

const Welcome = () => {
  return (
    <div className="welcome">
      <div className="intro">
        <h1 className="intro-title">Welcome to my GitHub profile! 👋🚀</h1>
        <p className="intro-text">
          My Name is Justin Praßl and I'm a 23 years old software developer from Germany. <br />
          I'm focusing on web development because I have the most fun making this, therefore I work <br />
          for a consulting company as a frontend developer (consultant) specialized in making UI5 frontends. <br />
          I also create UI / UX designs in addition and I'm studying business informatics. <br />
          Feel free to visit my <a href="https://justinprassl.de/">website</a>!
        </p>
      </div>
      <div className="misc">
        <ul className="skills">
          <li className="skills-item">HTML5 & CSS3</li>
          <li className="skills-item">JavaScript (NodeJS, React, Next, Svelte, UI5) & PHP</li>
          <li className="skills-item">Java & C#</li>
          <li className="skills-item">SQL (Oracle, MariaDB & MySQL) & NoSQL (Mongo & Redis)</li>
          <li className="skills-item">REST- & GraphQL APIs</li>
          <li className="skills-item">UI / UX Design</li>
        </ul>
      </div>
    </div>
  )
}

export default Welcome
```
