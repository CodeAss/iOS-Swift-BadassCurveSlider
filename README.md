# iOS-Swift-BadassCurveSlider
A iOS Curve Slider created by Badass.

Example:
let slider=BadassCurveSlider()
//set border color:
leftSlider.borderColor=UIColor(hexString: "#8D52BE")
//set filled color
leftSlider.fillColor=UIColor(hexString: "#6E6FFF")
//set min&max value
leftSlider.minValue=5
leftSlider.maxValue=100
//didEndSlide is called when user released touch with value
leftSlider.didEndSlide={(value) in
	print("end slide",value)
}
