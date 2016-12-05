# Prior Art

## Metadata Files

### OSSMETADATA

Developed and used by Netflix to initially power their internal project dashboards.

**Example:** <https://github.com/Netflix/edda/blob/master/OSSMETADATA>

### .google/packaging.yaml

Developed and used by Google to document and package sample projects.  One
primary use of this data is to power the sample project directory inside of
[Android Studio](https://developer.android.com/studio/).

**Example:** <https://github.com/googlesamples/android-StorageProvider/blob/master/.google/packaging.yaml>

### about_yaml

Developed at [18F](https://18f.gsa.gov) initially for their own projects.
Documented as powering the [18F Dashboard](https://18f.gsa.gov/dashboard)
(though no longer appears to be active).

**Docs:** <http://www.rubydoc.info/gems/about_yml/0.0.10>  
**Example:** <https://github.com/18F/about_yml/blob/master/.about.yml>

## README Badges

One common ad hoc way of expressing some of this metadata is through badges
embedded in README files.  These badges have the advantage of being very
visibile, and therefore more likely to stay up to date.  However, they are not
as easily machine parseable for use in other applications.  A few of these
projects that document types of metadata we may be interested in:

 - <https://github.com/orangemug/stability-badges>
 - <https://github.com/insin/caveat-utilitor>
 - <https://github.com/danielbachhuber/statemarks>
