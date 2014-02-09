# Job Colors for WP Job Manager Categories #

<table>
	<td width="50%">
		<img src="https://smyl.es/img/Selection-1470x629-53.png">
	</td>
	<td width="50%"><img src="https://smyl.es/img/Selection-886x748-50.png"></td>
</table>

Plugin | Details
--- | ---
**Author URI**: | http://smyl.es<br>
**Plugin URI**: | http://github.com/tripflex/wp-job-manager-cat-colors<br>
**Contributors:** | SpencerFinnell, Myles McNamara<br>
**Tags:** | `job` `job listing` `job region` `job categories` `job category` `job color`<br>
**Requires at least:** | 3.5<br>
**Tested up to:** | 3.8<br>
**Stable Tag:** | 1.0<br>
**License:** | GPLv3<br>
**License URI:** | http://www.gnu.org/licenses/gpl-3.0.html<br>

Change a job category color without editing CSS.  This plugin was created from Astoundify's Job Colors for Job Types. You will need to add some HTML and PHP code to your template file in order to display the Job Category with the included styling.

## Description ##

Select the color of each existing job category in the Job Listings' settings. Can set the color to be the background color, or text color.

## Template Code ##
Insert the code below in your template to output the job category with the included styling.  The job-category class is used to set the
`<li class="job-category <?php echo get_the_job_category() ? sanitize_title( get_the_job_category()->slug ) : ''; ?>"><?php the_job_category(); ?></li>`

### Features ###
* Set color as background
* Set color as text
* Job Category public functions

### Requires ###
* [WP Job Manager by Mike Jolley](http://mikejolley.com/projects/wp-job-manager/)

### Recommended ###
* [Job Colors for WP Job Manager Types by Astoundify](https://github.com/Astoundify/wp-job-manager-colors)
* [Jobify Wordpress Theme by Astoundify](http://themeforest.net/item/jobify-job-board-wordpress-theme/5247604?ref=tripflex)

### Documentation ###

Documentation will be maintained on the [GitHub Wiki here](http://github.com/tripflex/wp-job-manager-cat-colors/wiki).

### Contributing and reporting bugs ###

You can contribute code and localizations to this plugin via GitHub: [http://github.com/tripflex/wp-job-manager-cat-colors](http://github.com/tripflex/wp-job-manager-cat-colors)

### Original Sources ###
* [Job Colors for WP Job Manager Types by Astoundify](https://github.com/Astoundify/wp-job-manager-colors)

### Support ###

If you spot a bug, you can of course log it on [Github](http://github.com/tripflex/wp-job-manager-cat-colors/issues)

Or contact me at myles@smyl.es

## Screenshots ##

https://smyl.es/img/Selection-886x748-50.png
https://smyl.es/img/Selection-698x209-51.png

## Installation ##

1. Install and Activate
2. Go to "Job Listings > Settings > Job Category Colors" and set colors.

## Frequently Asked Questions ##

## Changelog ##

### 1.0: Feb 9, 2014 ###

* First official categories release