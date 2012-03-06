# CodeIgniter Foundation #

### CodeIgniter pre-configured with Sparks and ion_auth. ###

### The Zurb Foundation CSS framework is also included. ###

The idea is to clone this repo whenever you start a new CI project. You then have sparks and a simple header/footer templating system to get going with using Zurb's Excellent CSS Foundation.

Check out the 'welcome' controller and 'template' view to see how my very simple templating system works.

Essentially it is thus:

    $data['page'] = "actual_view_you_want_to_load";

    $this->load->view('template', $data);

No need to worry about the header or footer, just start your page from inside the .container div.

### Don't forget to import the ion_auth sql tables into your database. ###