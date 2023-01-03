## Basic setup
  function Test() {
            const bla = () => alert("Hello you clicked react test component")
            return <button onClick={bla}>Click Me!</button>
        }
        class Hello extends React.Component {
            render() {
                return <div>Hello React with code <Test /></div>
            }
        }
        ReactDOM.render(<Hello />, document.getElementById("mydiv"))

