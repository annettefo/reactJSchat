ReactJS Chat Application
* Opensource Javascript Web App Framework
* JSX (syntax): HTML  mixed with JS
* Modular components
* One way data flow
* Rich ecosystem - components, tools
* Used by Facebook


*Example Code
// class to ask a user a question

class MyApp extends Component {
  render() {
    return <div className='hbox'>
      <label> Hello {this.props.username}</label>
      <button> Abort </button>
      <button onClick={this.props.onRetry}>Return</button>
      <button> Catch on fire </button>
    </div>
  }
}
<MyApp username=:"annette" onRetry={()=> console.log("retured")}/>

*ReactJS Commands

* npm start : starts the development server
* npm run build: bundles the app into static files for production
* npm test: starts the test runner
* npm run eject: Removes this tool and copies build dependencies, configuration, files, and scripts into the app directory. If you do this, you cannot go back!

Begin by -

cd <folder>
npm start


To create a production build, use npm run build.

Happy Hacking!
