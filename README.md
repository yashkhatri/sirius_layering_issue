# sirius_layering_issue

Steps to reproduce the issue:

1. Import these projects in eclipse.
    a. org.eclipse.sirius.sample.basicfamily
    b. org.eclipse.sirius.sample.basicfamily.edit
    c. org.eclipse.sirius.sample.basicfamily.editor
    
2. Start a new instance of eclipse by running this project as a Eclipse Application.

3. In the new eclipse instance import these projects:
    a. org.eclipse.sirius.sample.basicfamily.advanced.design
    b. LayeringIssue
    
4. Open project LayeringIssue.
  4.1 Expand My.basicfamily
  4.2 Expand Family
  4.2 Double click new Persons diagram
  
Issue: The PersonsDiagram should have the Man Layer active by default. But, it doesnot happen.

Good to know:
1.Previously, Man Layer did not exist and the elements and tool section in the Man Layer was under Default Layer.
2.The LayeringIssue Project was created based on this viewpoint.
3. LayeringIssue project is closed.
4. Now, The restructuring of the Default layer is done and the Tools and elemets are now moved to Man layer.
5. The Man Layer is set to be active by default. 
When opening the previously created LayeringIssue->persons diagram. Expectation is that the Man Layer should be active by default. But, it doesnot happen. 
