"# my own project" 
Das ist ein `markdown` test.

![blue flowers](https://github.com/DanielM812/ownProject/blob/master/blueFlowers.png)

	class SpinController : public osgGA::GUIEventHandler
	{
	public:
	    SpinController(osg::AnimationPathCallback* Apathcb, std::string name) : wegCB(Apathcb), model(name) {
	    }

	    virtual bool handle(const osgGA::GUIEventAdapter& ea, osgGA::GUIActionAdapter& aa);

	protected:
	    osg::ref_ptr<osg::AnimationPathCallback> wegCB;
	    std::string model;
	    bool spinning = false;
	};