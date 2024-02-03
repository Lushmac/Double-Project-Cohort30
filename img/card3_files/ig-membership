    function addToIG(ig) {
        if (navigator.joinAdInterestGroup) {
            try {
                navigator.joinAdInterestGroup(ig, 2592000000);
            } catch(e) {
                fetch('https://ams.creativecdn.com/ig-membership' + '?ig='+ encodeURIComponent(ig.name) + '&err=' +  encodeURIComponent(e.toString().substring(0, 256))).catch(() => {});
            }
        }
    }

    
