# nodejs-mailsending

# git clone https://github.com/sudhanshu647/nodejs-mailsending.git

# npm i

change gmail user name and password

# npm start

----------

// Create a SMTP transporter object
    const transporter = nodemailer.createTransport({
        host: Host do gmail precisa de mais solicitações.
        port: Manter porta 587
        auth: {
            user: e-mail de acesso
            pass: senha de acesso
        }
    });

    // Message object
    let message = {
        from: de, declarando o remetente
        to: para, declarando o destinatário. Para mais de um, utilizar 'abc <abc@gmail.com>, bcd <bcd@gmail.com>'
        subject: Título do e-mail
        text: Corpo do e-mail
        html: Modificações html do corpo do e-mail
    };
