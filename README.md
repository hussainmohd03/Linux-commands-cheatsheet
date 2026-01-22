
from odoo import models, fields, api


class Teacher(models.Model):
    _name = "training.teacher"
    _description = "Training Teacher"

    name = fields.Char(string="Teacher Name", required=True)
    code = fields.Char(string="Code", required=True)
