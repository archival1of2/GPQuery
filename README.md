GPQuery
============

## Overview

**GPQuery** is a [data visualisation][wiki-datavis] web application for historical Grand Prix Racing records dating back to 1950, written in Javascript and PHP by Jonathan Ho <joho@joho.us> as an educational and research project in full-stack development.

GPQuery consists of two custom-built applications: a front-end user interface written in [AngularJS][angular]; a back-end REST service based on an innovative pairing of [Slim Framework][slim] and [Laravel's][laravel] [Eloquent ORM][eloquent].

A third component comes in the form of a [MySQL][mysql] database and dataset provided by [Ergast Developer API][ergast]; this trio of components bears resemblance to a three-tier software architecture pattern.


## Structure

`GPQuery\Dashboard` - AngularJS front-end
`GPQuery\Engine` - Slim + Eloquent back-end


## Legal

*Please note that this section is still being developed and may contain incomplete or inaccurate statements.*

### Licence

See `LICENSE`.

### Fair Use

Due to the research and education nature of this work, the doctrine of [fair use][wiki-fairuse] introduces different terms and conditions behind the limited use of copyrighted material.  

The aforementioned information can be found in United States law under the Copyright Act of 1976, [17 U.S.C. § 107](http://www.law.cornell.edu/uscode/text/17/107).

### Trademarks

This project is unofficial and is not associated in any way with the Formula One group of companies. F1, FORMULA ONE, FORMULA 1, FIA FORMULA ONE WORLD CHAMPIONSHIP, GRAND PRIX and related marks are trade marks of Formula One Licensing B.V.[Source](http://www.formula1.com/trademarkguidelines.html)


## Version History

| Version | Date        | Description |
|:--------|:-----------:|:------------|
|  0.0.1  | 08/01/2015  | First draft; initial commit. |



[wiki-datavis]:http://en.wikipedia.org/wiki/Data_visualization
[wiki-fairuse]:http://en.wikipedia.org/wiki/Fair_use


[ergast]:http://ergast.com/mrd
[mysql]:http://mysql.com
[slim]:http://slimframework.com
[angular]:http://angularjs.org
[laravel]:http://laravel.com
[eloquent]:http://laravel.com/docs/eloquent