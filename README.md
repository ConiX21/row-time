# Row timer
` for (var i = 0; i < persons.length; i++) {
            setTimeout((a) => {
                var $template = $("#rowTemplate").html();
                var render = Mustache.render($template, persons[a]);
                $("tbody").append(render);

            },i * 1500, i);
        }
`

