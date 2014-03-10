ngTriState
==========

AngularJS Directive for a Tri State Checkbox.


##Usage

    HTML
    <input type="checkbox" cbx-tri-state ng-model="checkbox.isSelected">
    
    JAVASCRIPT
    $scope.checkbox =  {isSelected: null}; 
    
#true = Checked
#false = Unchecked
#null = Indeterminate
