# codewars 
function duplicateCount(text){

return (text.toLowerCase().split('').sort().join('').match(/([^])\1+/g) || []).length
                        
                       
  
  }
