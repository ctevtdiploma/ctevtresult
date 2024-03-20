<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Office of the Controller of Examinations · Sanothimi, Bhaktapur · Yearly/Semester Check Results. </title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <link rel="stylesheet" href="https://itms.ctevt.org.np:5580/public/css/bootstrap.css" media="screen">

    <link href="https://itms.ctevt.org.np:5580/public/fontawesome/css/fontawesome.min.css" rel="stylesheet">
    <link href="https://itms.ctevt.org.np:5580/public/fontawesome/css/solid.min.css" rel="stylesheet">

    <link href="https://itms.ctevt.org.np:5580/public/css/style.css" rel="stylesheet">

    <link href="https://itms.ctevt.org.np:5580/public/css/dataTables.bootstrap5.min.css" rel="stylesheet">
    <link rel="icon" type="image/png" sizes="16x16" href="https://itms.ctevt.org.np:5580/public/img/favicon.ico">
    <script src="https://itms.ctevt.org.np:5580/public/js/jquery-3.6.0.min.js"></script>

    <!-- HTML5 shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="../bower_components/html5shiv/dist/html5shiv.js"></script>
      <script src="../bower_components/respond/dest/respond.min.js"></script>
    <![endif]-->

    <noscript>
        <meta http-equiv="refresh" content="0.0;url=nojs.php">
    </noscript>
</head>

<body>
    <div class="col-lg-6 col-md-8 col-sm-10 mx-auto">
        <div class="jumbotron">
            <h5>Yearly/Semester Check Results</h5>

        </div>
        <div class="form_jumbotron">
            <div class="col-lg-6 col-md-8 col-sm-10 mx-auto" style="margin-top:0px;">
                <form name="frmCheckResults" id="frmCheckResults" action="https://itms.ctevt.org.np:5580/search_results"
                    method="post" target="_blank" autocomplete="off">
                    <div class="row">
                        <label for="" class="col-lg-6 col-md-8 col-sm-10 mx-auto">Examination Year:</label>
                        <div class="col-lg-6 col-md-8 col-sm-10 mx-auto">
                            <select required name="src_year" id="src_year" class="form-control">
                                <option value="">-- Select --</option>
                                </option>
                                <option value="2081">
                                    2081
                                <option value="2080">
                                    2080 </option>
                                <option value="2079">
                                    2079 </option>
                                <option value="2078">
                                    2078 </option>
                                <option value="2077">
                                    2077 </option>
                                <option value="2076">
                                    2076 </option>
                                <option value="2075">
                                    2075 </option>
                                <option value="2074">
                                    2074 </option>
                                <option value="2073">
                                    2073 </option>
                                <option value="2072">
                                    2072 </option>
                                <option value="2071">
                                    2071 </option>
                                <option value="2070">
                                    2070 </option>

                            </select>
                        </div>
                    </div>
                    <br />
                    <div class="row">
                        <label for="" class="col-lg-6 col-md-8 col-sm-10 mx-auto">Level :</label>
                        <div class="col-lg-6 col-md-8 col-sm-10 mx-auto">
                            <select name="src_level" id="src_level" class="form-control" required>
                                <option value="">-- Select --</option>
                                <option value="2">Pre-diploma</option>
                                <option value="3">Diploma/PCL</option>
                            </select>
                        </div>
                    </div>
                    <br />
                    <div class="row">
                        <label for="" class="col-lg-6 col-md-8 col-sm-10 mx-auto">Symbol Number :</label>
                        <div class="col-lg-6 col-md-8 col-sm-10 mx-auto">
                            <input type="text" name="exam_symbol_number" id="exam_symbol_number" class="form-control"
                                placeholder="e.g. 1000234" required>
                        </div>
                    </div>
                    <br />
                    <div class="row">
                        <label for="" class="col-lg-6 col-md-8 col-sm-10 mx-auto">Date of Birth (B.S.) :</label>
                        <div class="col-lg-6 col-md-8 col-sm-10 mx-auto">
                            <input type="text" name="dob" id="dob" placeholder="Date Format: YYYY-MM-DD"
                                class="form-control" required>
                        </div>
                    </div>
                    <br />
                    <div class="col-lg-12 text-center"><input type="submit" name="submit" value="Search"
                            class="btn btn-primary"></div>
            </div>
            </form>
        </div>
    </div>

    <script type="text/javascript">
        $(document).ready(function () {

            // toggle between inst and ctevtuser
            $("#classified_box").hide();
            $("#full_paying_box").hide();
            $("#src_application_type").change(function () {
                if ($(this).val() != '') {
                    if ($(this).val() == '5') {
                        $("#classified_box").hide();
                        $("#src_user").removeAttr('required');
                        $("#full_paying_box").show();
                        $("#src_dist").attr('required');
                        $("#src_institute").attr('required');
                    }
                    else {
                        $("#full_paying_box").hide();
                        $("#src_dist").removeAttr('required');
                        $("#src_institute").removeAttr('required');
                        $("#classified_box").show();
                        $("#src_user").attr('required');
                    }
                }
            });
            // end of toggle between inst and ctevtuser

            $("#src_level").change(function () {
                var src_level = $(this).val();
                $.post("https://itms.ctevt.org.np:5580/ajax/getFacultyByLevel/",
                    { sel_level: src_level },
                    function (data) {
                        $("#src_faculty").html(data);
                        //alert(data);
                    });
            });


            $("#src_faculty").change(function () {
                var src_level = $("#src_level").val();
                var sel_faculty = $("#src_faculty").val();
                $.post("https://itms.ctevt.org.np:5580/inst_report/getSubFacultyByLevelAndFaculty/",
                    { sel_level: src_level, sel_faculty: $(this).val() },
                    function (data) {
                        $("#src_sub_faculty").html(data);
                        //alert(data);
                    });
            });

            $("#src_sub_faculty").change(function () {
                var src_level = $("#src_level").val();
                var sel_faculty = $("#src_sub_faculty").val();
                $.post("https://itms.ctevt.org.np:5580/student_performance/showYearSemester/",
                    { sel_level: src_level, sel_faculty: $(this).val() },
                    function (data) {
                        $("#src_year_semeter").html(data);
                        //alert(data);
                    });
            });

            $("#src_sub_faculty").change(function () {
                var level = $("#src_level").val();
                var faculty = $("#src_faculty").val();
                var sub_faculty = $("#src_sub_faculty").val();

                if (level == '' || faculty == '' || sub_faculty == '') {
                    alert('Please select Level, Faculty and Trade !!');
                }
                else {
                    $.post("https://itms.ctevt.org.np:5580/inst_report/getInstituteByProgram/",
                        {
                            /*sel_team: team_cd,
                            sel_level:  level, 
                            sel_faculty: faculty,*/
                            sel_program: sub_faculty
                        },
                        function (data) {
                            //alert(data);
                            $("#src_institute").html(data);
                        });
                    $.post("https://itms.ctevt.org.np:5580/inst_report/getInstituteDistrictByProgram/",
                        {

                            sel_level: level,
                            sel_faculty: faculty,
                            sel_program: sub_faculty
                        },
                        function (data) {
                            //alert(data);
                            $("#src_dist").html(data);
                        });
                }
            });
            $("#src_dist").change(function () {
                var level = $("#src_level").val();
                var faculty = $("#src_faculty").val();
                var sub_faculty = $("#src_sub_faculty").val();
                //var active_edu_year = $("#active_edu_year").val();
                var dist = $("#src_dist").val();

                //alert(faculty+sub_faculty+dist);

                if (faculty == '' || sub_faculty == '' || dist == '') {
                    alert('Please select Level, Faculty, Program and District !!');
                }
                else {
                    $.post("https://itms.ctevt.org.np:5580/inst_report/getInstituteByProgramAndDistrict/",
                        {
                            sel_level: level,
                            sel_faculty: faculty,
                            sel_program: sub_faculty,
                            sel_dist: dist
                        },
                        function (data) {
                            //alert(data);
                            $("#src_institute").html(data);
                        });

                }
            });

        });
    </script>

    </footer>


    </div>


    <script src="https://itms.ctevt.org.np:5580/public/js/bootstrap.min.js"></script>

    <script src="https://itms.ctevt.org.np:5580/public/js/jquery.dataTables.min.js"></script>
    <script src="https://itms.ctevt.org.np:5580/public/js/dataTables.bootstrap5.min.js"></script>
    <script src="https://itms.ctevt.org.np:5580/public/js/acmeticker.js"></script>
    <script src="https://itms.ctevt.org.np:5580/public/js/nepali.datepicker.v3.2.min.js"></script>
    <script>
        $(document).ready(function () {

            table = $('#table1').DataTable({
                "destroy": true,
                "processing": true,
                "serverSide": true,
                "ajax": {
                    url: "notices/get-ajax-notices",
                    data: { "tab_id": 'tab-0' }
                },

                "columns": [
                    { "data": "serial_no" },
                    { "data": "updated_date" },
                    { "data": "notice_title" },
                    { "data": "notice_files" },
                    { "data": "publisher" },
                ],

                'columnDefs': [
                    {
                        "targets": 0,
                        "className": "text-center",
                        "orderable": false
                    },
                    {
                        "targets": 1,
                        "orderable": false
                    },
                    {
                        "targets": 2,
                        "orderable": false
                    },

                    {
                        "targets": 3,
                        "className": "text-center",
                        "searchable": false,
                        "orderable": false

                    },
                    {
                        "targets": 4,
                        "orderable": false
                    }
                ]

            });

            $('body').on('click', '.nav-link', function () {

                var id = $(this).attr('id');

                table = $('#table1').DataTable({
                    "destroy": true,
                    "processing": true,
                    "serverSide": true,
                    "ajax": {
                        url: "notices/get-ajax-notices",
                        data: { "tab_id": id }
                    },

                    "columns": [
                        { "data": "serial_no" },
                        { "data": "updated_date" },
                        { "data": "notice_title" },
                        { "data": "notice_files" },
                        { "data": "publisher" },
                    ],

                    'columnDefs': [
                        {
                            "targets": 0,
                            "className": "text-center",
                            "orderable": false
                        },
                        {
                            "targets": 1,
                            "orderable": false
                        },
                        {
                            "targets": 2,
                            "orderable": false
                        },

                        {
                            "targets": 3,
                            "className": "text-center",
                            "searchable": false,
                            "orderable": false

                        },
                        {
                            "targets": 4,
                            "orderable": false
                        }
                    ]

                });

            });


            $('.notice-body').AcmeTicker({
                type: 'marquee',/*horizontal/horizontal/Marquee/type*/
                direction: 'left',/*up/down/left/right*/
                speed: 0.04,/*true/false/number*/ /*For vertical/horizontal 600*//*For marquee 0.05*//*For typewriter 50*/
                controls: {
                    toggle: $('.acme-news-ticker-pause'),/*Can be used for horizontal/horizontal/typewriter*//*not work for marquee*/
                }
            });
        })

        //nepali date
        currMonth = NepaliFunctions.GetCurrentBsMonth();
        currDay = NepaliFunctions.GetCurrentBsDay();
        currYear = NepaliFunctions.GetCurrentBsYear();

        day = NepaliFunctions.GetBsFullDayInUnicode({ year: currYear, month: currMonth, day: currDay });
        currentDate = NepaliFunctions.GetBsFullDate({ year: currYear, month: currMonth, day: currDay }, true);

        full_date = day + ', ' + currentDate;
        document.getElementById("nepali_date").innerHTML = full_date;

    </script>
</body>

</html>
