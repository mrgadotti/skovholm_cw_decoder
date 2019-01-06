// $Id: media_browser.js,v 1.6 2009/06/09 12:52:24 antoniodemarco Exp $

 if (Drupal.jsEnabled) {  

    var media_browser_bind = function(display) {
      $('.media_browser_link.' + display + ' > a').click(function(link, data) {
      
        var media_browser_update_html = function(data) {
          $('.media_browser_attachment.' + display).html(data.attachment);
        }
        $.ajax({
          type: 'POST',
          url: $(this).attr('href'),
          dataType: 'json',
          success: media_browser_update_html,
          data: 'js=1'
        });
        return false;
      });
    }

//  $(document).ready(function() { 
//    media_browser_bind();    
//  });
  
  // In case of AJAX pager, re-bind links
//  $().bind('ajaxComplete', function() {
//    media_browser_bind();    
//  });  
}