# Test_APP
//Small simple app for test learning 
///the codes below
mport UIKit

class ViewController: UIViewController {
    var A: String = " Helo!"
    var B: String = "  Welcome ! "
    var C: String = "  Thank YOU !"

    @IBOutlet weak var label: UILabel!
    override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view.
    }

    @IBAction func A(_ sender: Any) { label.text = A
        
        }
    @IBAction func B(_ sender: Any) { label.text = B
        
    }
    @IBAction func C(_ sender: Any) { label.text = C
    }
    @IBAction func D(_ sender: Any) { label.text = "              "
        
    }
}
    
