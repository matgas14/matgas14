
// Follow this link to open readMe in codesandbox: https://codesandbox.io/s/matej-gaspert-readme-iuivp5?file=/src/App.js

export default function App() {
  return (
    <div className="app">
      <div className="container">
        <h1>Hello Viewer!</h1>
        <h2>Seems like you've stumbled upon my github page...</h2>
      </div>
      <div className="container-reverse">
        <h3>About me</h3>
        <span className="info-text">
          Young and ambitious, I am always looking to expand and sharpen my
          skills and knowledge. I have been working for the past two years as a
          front end developer with React.js. I am interested in enhancing my
          React skills as well as learning new technologies. My focus is on
          frontend development but my future goal is to be a full-stack
          developer.
        </span>
        <span className="info-text">
          I am currently developing responsive websites for individual client
          projects and I have worked on Atlassian Apps and products. I have
          experience in building apps and pages from scratch as well as updating
          and/or fixing bugs on existing apps and websites.
        </span>
      </div>
      <div className="container">
        <h3>What I'm looking for...</h3>
        <span className="info-text">
          I am looking for a challenging and healthy environment where I would
          have the chance both to work independently on interesting projects,
          and have the opportunity to learn and grow as a developer.
        </span>
      </div>
      <div className="container-reverse">
        <h3>How to reach me</h3>
        <div className="contact">
          <div className="contact-item">
            +385 99 750 5839
          </div>
          <div className="contact-item">
            <a href="https://www.linkedin.com/in/matgas14/">
              https://www.linkedin.com/in/matgas14/
            </a>
          </div>
          <div className="contact-item">
            matejgaspert23@gmail.com
          </div>
        </div>
      </div>
    </div>
  );
}
